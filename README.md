# TryBeer Project

## Tabela de conteúdos

- [Sobre](https://github.com/LeonardoCavachini/TryBeer.git#Sobre)
- [Instalação](https://github.com/LeonardoCavachini/TryBeer.git#Instalação)
- [Como-usar](https://github.com/LeonardoCavachini/TryBeer.git#Como-usar)
- [Tecnologias](https://github.com/LeonardoCavachini/TryBeer.git#Tecnologias)

## Sobre

Aplicação tem dois ambientes `Client` e `administrator`, onde o `Client` pode escolher um tipo de cerveja e fazer uma solicitão de compra, onde e fornecido um endereço de entrega, o `administrator` recebe a solicitão e envia status dobre o pedido.

## Instalação

#### Pré-requisitos

Certifique-se de ter instalado em sua maquina estas ferramentas: Git, Node.js, MySQL, MongoDB e um editor de textos como o VSCode.

#### Rodando a aplicação localmente

1. Clone o repositório

- `git clone https://github.com/LeonardoCavachini/TryBeer.git`

2. Entre na pasta do repositório que você acabou de clonar:

- FrontEnd:

- `cd front-end`

3. Instale as dependências:

- `npm install`

- Inicie o projeto com `npm start`  
  Por padrão o React procura rodar as aplicações na porta 3000.
  Uma página no browser será aberta com a aplicação.  
  Divirta-se!!

- BackEnd:

- `cd back-end`

- `npm install`

- adicione um arquivo `.env` com as seguintes vaiaveis de ambiente.

MYSQL_USER=`exemplo: root`

MYSQL_PASSWORD=`exemplo: 123`

HOSTNAME=`exemplo: localhost`

DB_URL=mongodb://localhost:27017

SCHEMA=Trybeer

DB_NAME=Trybeer

- Inicie o projeto com `npm run debug`

  O projeto irá iniciar o backend na porta 3001.

## Como Usar

Ao iniciar a aplicação o usuário deverá logar-se, caso não tenha um login cadastrado havera um botão para o mesmo.

Quando você estiver na pagina de login, haverá uma opção de `Quero Vender`, quando essa opção é marcada o usuário se torna `administrator`.

Após Registro, quando você é `Client`, você será direcionado a uma pagina onde mostra um catalago de cervejas, ali você pode escolher a cerveja desadae fazer seu pedido, quando você loga como `adminstrator`, você é direcionado a uma pagina onde mostra todas as seus pedidos e assim vc pode enviar status.

## Tecnologias

Tecnologias utilizadas para construção da aplicação:

- Node
- React
- Socket.io
- banco de dados: mysql / mongodDB

Ferramentas para controle e organização de código:

- ESLint
- Git
