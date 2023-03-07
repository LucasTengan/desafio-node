
# Desafio Node

O desafio consistem em utilizar o nginx como proxy reverso, que redicionará a chamada para a aplicação em node.js e essa aplicação adicionará um registro no banco de dados mysql, cadastrando um nome na tabela people.

Ao acessar a rota localhost:8080, deve ser exibida a mensagem:
```html
<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrada no banco de dados.
```

Para executar a aplicação, execute o comando: `docker-compose up`

Ela estará disponível em: localhost:8080
