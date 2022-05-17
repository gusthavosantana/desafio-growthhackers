<h1 align="center">Desafio Growth Hackers - Frontend</h1>

<p align="center">Este projeto representa a interface de usuário e tem como objetivo permitir o cadastro, importação e exportação de produtos e cadastro de categorias.</p>

Índice
=================
<!--ts-->
   * [Instalação](#instalacao)
     * [Local](#local)
     * [Docker](#docker)
   * [Como usar](#como-usar)
   * [Features](#features)
   * [Tecnologias](#tecnologias)
<!--te-->


<h2 id="instalacao">Instalação</h2>

<h4 id="local">Instalação local</h4>

Para rodar a aplicação de forma local (na sua máquina), siga os passos abaixo:
### Clone este repositório
```
$ git clone https://github.com/gusthavosantana/desafio-growthhackers-frontend.git
```
### Acesse a pasta do projeto
```
$ cd desafio-growthhackers-frontend
```

### Variáveis de ambiente
Copie o arquivo .env.example, renomeie para .env e preencha as variáveis de ambiente.

### Instale as dependências
```
$ yarn
```

<h4 id="docker">Docker</h4>

Outra forma rodar a aplicação é usando docker, para isso siga os passos abaixo:

### Clone este repositório
```
$ git clone https://github.com/gusthavosantana/desafio-growthhackers-frontend.git
```

<h2 id="como-usar">Como usar</h2>

### Faça o build da aplicação
```
$ yarn build
```
### Inicie o servidor
```
$ yarn start
```

### Acesse a aplicação
Para acessar a aplicação use o endereço: `http://localhost:PORT`. Sendo que <b>PORT</b> é o número da porta onde a aplicação irá executar definido na variável de ambiente de nome PORT. Caso o valor seja o padrão (3000) o endereço será http://localhost:3000.

<h2 id="features">Features</h2>

- [x] Listar categorias
- [x] Cadastrar categorias
- [x] Atualizar categorias
- [x] Excluir categorias
- [x] List produtos de uma categoria
- [x] Cadastrar produtos em uma categoria
- [x] Atualizar produtos de uma categoria
- [x] Excluir produtos de uma categoria
- [x] Importar produtos para uma categoria
- [x] Exportar produtos de uma categoria

<h2 id="tecnologias">🛠 Tecnologias</h2>

As seguintes ferramentas foram usadas para construir este projeto:

- [React](https://nodejs.org/en/)
- [React Router DOM](https://reactrouterdotcom.fly.dev/)
- [MUI](https://mui.com/)
- [TypeScript](https://www.typescriptlang.org/)