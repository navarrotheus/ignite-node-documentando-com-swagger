<a href="https://github.com/navarrotheus/ignite-node-challenges">
  <img alt="Ignite Node" src="https://i.ibb.co/qrrkc3T/Background.png" />
</a>

<p align = "center">
  <a href="https://github.com/navarrotheus/ignite-node-challenges">Ver todos desafios</a>
</p>

<p align = "center">
   <a href="#descrição-memo">Descrição</a>&nbsp;|
   <a href="#rotas-airplane">Rotas</a>&nbsp;|
   <a href="#instruções-scroll">Instruções</a>
</p>

## Descrição :memo:
Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no Node.js!

Utilizando uma aplicação já funcional como base, realize a documentação das rotas com o Swagger.

A aplicação funcional será a do desafio passado: [ignite-node-introducao-ao-SOLID](https://github.com/navarrotheus/ignite-node-introducao-ao-SOLID)

## Rotas :airplane:

### POST `/users`

A rota deve receber `name`, e `email` dentro do corpo da requisição para que seja possível cadastrar um usuário.

### PATCH `/users/:user_id/admin`

A rota deve receber, nos parâmetros da rota, o `id` de um usuário e transformar esse usuário em admin.

### GET `/users/:user_id`

A rota deve receber, nos parâmetros da rota, o `id` de um usuário e devolver as informações do usuário encontrado pelo corpo da resposta.

### GET `/users`

A rota deve receber, pelo header da requisição, uma propriedade `user_id` contendo o `id` do usuário e retornar uma lista com todos os usuários cadastrados. O `id` deverá ser usado para validar se o usuário que está solicitando a listagem é um admin. O retorno da lista deve ser feito apenas se o usuário for admin.

## Instruções :scroll:

Para baixar as dependências:
```yarn```

Rodar os testes:
```yarn test```

Rodar a API em modo de desenvolvimento:
```yarn dev```

Para acessar a documentação, após rodar a API, acesse a rota:
```/api-docs```

<hr>

<p align = "center">
  <a href="#">Voltar ao topo</a>
</p>
