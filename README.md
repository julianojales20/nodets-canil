# nodets-canil
Projeto feito no módulo do curso Node + Typescript

### Pré- requisitos globais:
`npm install -g nodemon typescript ts-node`

### Instalação
`npm install`

### Para rodar o projeto
`npm run start-dev`

### Passo a passo criação do Projeto

1 - Criar um Repositório do Github
2 - Clonar o Repositório em uma pasta
3 - Abrir o projeto no Studio Code e Entrar no Terminal
4 - npm init
5 - tsc --init
6 - Editar o Arquivo tsconfig.json
	"target": "ES6",
	"rootDir": "./src",
	"outDir": "./dist",
	"moduleResolution": "node",
7 - Dependencias
	npm install express@4.17.1
	mustache-express@1.3.1
	dotenv@10.0.0
8 - Dependencias DEV
	npm install --save-dev @types/express@4.17.12 @types/mustache-express@1.2.1 @types/node@16.0.0
9 - Criar a pasta
	Src
10 - Criar o arquvo
	Server.ts
11 - package.json
	"start-dev": "nodemon -e ts,jason,mustache src/server.ts"