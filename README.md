<h1 align="center">
  <img alt="logo" width="450px"  title="#Be The Hero" src="./assets/logo.svg" />
</h1>

<h4 align="center"> 
	🚧 Be The Hero 🚀 concluído 🚧
</h4>

<br/>

<p align="center">
 <a href="#sobre-o-projeto">Sobre o projeto</a> • 
 <a href="#funcionalidades">Funcionalidades</a> • 
 <a href="#layout">Layout</a> • 
 <a href="#como-executar-o-projeto">Como executar o projeto</a> • 
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#contribuidores">Contribuidores</a> • 
 <a href="#autor">Autor</a> • 
<a href="#licenc-a">Licença</a> • 
</p>
<br/>

## Sobre o projeto

<p align="left">Be The Hero é uma plataforma que ajuda Ongs a encontrar pessoas que estão dispostas a ajudar em algumas situações. Basta o usuário cadastrar a Ongs em seguida cadastrar algum caso que precisa de ajuda, seja uma ajuda financeira ou mão de obra.

Projeto desenvolvido durante a semana OmniStack 11 oferecida pela  [Rocketseat](https://blog.rocketseat.com.br).. O OmniStack é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.
</p>

<br/>

##  Funcionalidades

- [x] Cadastro de usuário.
  - [x] Cadastro de ONGS.
  - [x] Exibi casos e Ongs cadastrados.
  - [x] Exibi informações detalhadas dos casos.
  - [x] Permiti entrar em contato com a ONG via Whatsapp
---

## Layout
Você pode acessar o Layout pelo Figma atravês <a href="https://www.figma.com/file/RNHajWbLbxioQgZ9WI829p/Be-The-Hero---OmniStack-11-(Copy)?node-id=0%3A1">desse link</a>.

<br/>
<h1>Versão Mobile</h1>
<h1 align="center">
  <img alt="Be The Hero"  title="#Be The Hero" src="./assets/preview.png" />
</h1>

<h1>Versão web</h1>
<p align="center">
  <img alt="Be The Hero"  width="450px" title="#Be The Hero" src="./assets/landing.png" />
  <img alt="Be The Hero"  width="450px" title="#Be The Hero" src="./assets/cadastro.png" />
  <img alt="Be The Hero"  width="450px" title="#Be The Hero" src="./assets/cadastroOng.png" />
</p>

---
## Como executar o projeto
Este projeto é divido em três partes:
1. Backend (pasta backend) 
2. Frontend (pasta web)
3. Mobile (pasta mobile)

anto o Frontend quanto o Mobile precisam que o Backend esteja sendo executado para funcionar.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com) e um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲Clonando o projeto

```bash

# Clone este repositório
$ git clone git@github.com:andersonzeroone/beTheHero-OmniStack11.git

# Acesse a pasta do projeto no terminal/cmd
$ cd beTheHero-OmniStack11

```
#### 🎲 Rodando o Backend (servidor)

```bash


# Acesse a pasta do projeto no terminal/cmd
$ cd backend

# Instale as dependências
$ npm install ou yarn install

# Execute a aplicação
$ npm start ou  yarn start 

# O servidor inciará na porta:3333 - acesse http://localhost:3333 

```
<!-- <p align="center">
  <a href="https://github.com/tgmarinho/README-ecoleta/blob/master/Insomnia_API_Ecoletajson.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p> -->

#### 🧭 Rodando a aplicação web (Frontend)

```bash

# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ npm install ou yarn install

# Execute a aplicação em modo de desenvolvimento
$ npm start ou  yarn start 

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000

```


#### 🧭 Rodando a aplicação mobile

```bash

# Vá para a pasta da aplicação Front End
$ cd mobile

# Instale as dependências
$ npm install ou yarn install

# Execute a aplicação em modo de desenvolvimento
$ expo start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000

acesse localhost:19002, leia o QR Code no seu celular e utilize o aplicativo Expo para rodar a versão mobile no seu smartphone. Ou com algum emulador Android/iOS para rodar no seu computador.

```
##  Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

**Backend**  [NodeJS](https://nodejs.org/en/) 
-   **[Express](https://expressjs.com/)**
-   **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**
-   **[KnexJS](http://knexjs.org/)**
-   **[SQLite](https://github.com/mapbox/node-sqlite3)***
-   **[Celebrate](https://github.com/arb/celebrate)**


> See the file  [package.json](https://github.com/andersonzeroone/beTheHero-OmniStack11/blob/main/backend/package.json)
> 

#### **Website**  ([React](https://reactjs.org/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
-   **[React Icons](https://react-icons.github.io/react-icons/)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Leaflet](https://react-leaflet.js.org/en/)**
-   **[React Leaflet](https://react-leaflet.js.org/)**


> See the file  [package.json](https://github.com/andersonzeroone/beTheHero-OmniStack11/blob/main/web/package.json)

**Mobile**  ([React Native](http://www.reactnative.com/))

-   **[Expo](https://expo.io/)**
-   **[Expo Google Fonts](https://github.com/expo/google-fonts)**
-    **[Expo Constants](https://docs.expo.io/versions/latest/sdk/constants/)**

-   **[Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)**
-   **[React Navigation](https://reactnavigation.org/)**
-   **[Axios](https://github.com/axios/axios)**

> Veja o arquivo  [package.json](https://github.com/andersonzeroone/beTheHero-OmniStack11/blob/main/mobile/package.json)


**Utilitários**

-   Protótipo:  **[Figma](https://www.figma.com/)**  →  **[Protótipo (Ecoleta)](https://www.figma.com/file/RNHajWbLbxioQgZ9WI829p/Be-The-Hero---OmniStack-11-(Copy)?node-id=0%3A1)**

-   Editor:  **[Visual Studio Code](https://code.visualstudio.com/)**  

-   Maps:  **[Leaflet](https://react-leaflet.js.org/en/)**

-   API Test:  **[Insomnia](https://insomnia.rest/)**

---
## Contribuidores

💜 Um super thanks 👏 para essa galera que fez esse produto sair do campo da ideia e entrar nas lojas de aplicativos :)

## Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](./CONTRIBUTING.md)

---

##  Autor
</br>

<a href="https://github.com/andersonzeroone">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/33969430?v=4" width="100px;" alt=""/>
 <br />
 <br />
 <sub><b>Anderson Pablo</b></sub></a> <a href="https://www.linkedin.com/in/anderson-pablo-js/" title="andersonPablo">🚀</a>
 <br />


 [![Linkedin Badge](https://img.shields.io/badge/-Anderson-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/anderson-pablo-js/)](https://www.linkedin.com/in/anderson-pablo-js/) 
[![Gmail Badge](https://img.shields.io/badge/-anderson.pablo02@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:anderson.pablo02@gmail.com)](mailto:anderson.pablo02@gmail.com)

---

## Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Anderson Pablo 👋🏽 [Entre em contato!](https://www.linkedin.com/in/anderson-pablo-js/)

---

<!-- ##  Versões do README

[Português 🇧🇷](./README.md)  |  [Inglês sem emojis 🇺🇸](./README-en.md) | [Portugues sem logo  🇧🇷](./README-sem-logo.md)  -->