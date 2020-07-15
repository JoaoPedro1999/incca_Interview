<p align="center">
<img src="logo.png" width="300" >
</p>

## Incca interview

## IncFinances

Financial transaction management application

## Requisites for running the Back End

Before you begin, you will need to have the following tools installed on your machine:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).

## Running the Back End (server)
### Deployed at: [Deploy](http://157.245.252.101/)

### Clone this repository
$ git clone https://github.com/JoaoPedro1999/incfinances-server.git

### Go to the server folder
$ cd server

### Create a Docker Container

### Configure database options

### Copy the ormconfig.example.json and change to ormconfig.json

### Run the migrations
$ yarn typeorm migration:run

### Install the dependencies
$ yarn

### Run the application in development mode
$ yarn dev:server

### The server will start at port: 3333 - go to <http: // localhost: 3333>

## Running the FrontEnd
### Deployed at: [Deploy](https://incfinances.vercel.app/)

### Clone this repository
$ git clone https://github.com/JoaoPedro1999/incfinances-frontend.git

### Go to the frontend folder
$ cd frontend

### Install the dependencies
$ yarn install

#### To run in local mode, change the archive src/services/api.ts
  baseURL: 'http://localhost:3333'

### Run the application in development mode
$ yarn start

## Tecnologias

The following tools were used in the development of the IncFinances application:

- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)

## Questions

To check the answers for the questions, visit: https://www.notion.so/joaopedrobeckland/Perguntas-Questions-8c3382f6841c4291a3f187d1f5c852ee

## Developer

 <img style="border-radius: 50%;" src="https://avatars3.githubusercontent.com/u/28880525?s=400&u=d81c22a8b60e75b36a01a52597036a650bfdd9aa&v=4" width="100px;" alt=""/>
 <br />
 <sub><b>João Pedro Beck Land</b></sub>

[![Gmail Badge](https://img.shields.io/badge/-joaopedrobeckland@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:joaopedrobeckland@gmail.com)](mailto:joaopedrobecklandgmail.com)
