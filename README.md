Exercício para conhecer o Express + NodeJS do curso técnico em informática do Senac Araraquara

# O que é uma API Restfull
--

# O que é o express?
--

# Intalação

Intalação do express
```sh
$ npm install express
```

Intalação do body-parser
```sh
$ npm install body-parser
```

## Exercício
Criar o sistema de rotas imaginando que você iniciará o desenvolvimento de um API Restfull para a listagem de produtos de um restaurante. Pense nos atributos que devem ter cada um dos produtos como nome, preço, descrição, imagem, etc.

Os rotas devem ser:

[GET] /produtos - lista de todos os produtos

[GET] /produtos/:id - lista de um único produto

[POST] /produtos - inserir um produto

[PUT] /produtos/:id - atualizar um produto

[DELETE] /produtos - remover um produto

Até o momento não fizemos a conexão com o banco de dados então deve-se utilizar um arquivo estático JSON para simular os dados.