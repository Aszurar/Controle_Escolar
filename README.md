# Controle Escolar | LaunchBase
 O projeto de Controle Escolar é uma plataforma de gerenciamento de estudantes e alunos de um sistema de ensino tanto a distância quanto presencial!!.
<h2 align="center">Controle Escolar</h2>

___

<h3 align="center">
  <a href="#information_source-sobre">Sobre</a>&nbsp;|&nbsp;
  <a href="#interrobang-motivo">Motivo</a>&nbsp;|&nbsp;
  <a href="#seedling-requisitos-mínimos">Requisitos</a>&nbsp;|&nbsp;
  <a href="#rocket-tecnologias-utilizadas">Tecnologias</a>&nbsp;|&nbsp;
  <a href="#package-como-baixar-e-executar-o-projeto">Baixar e Executar</a>&nbsp;
</h3>

___

<div align="center" ><img src="" width="600"></div> 

___

## :information_source: Sobre

O projeto de Controle Escolar é uma plataforma web voltada para o gerenciamentos de um sistema de ensino a distância e presencial.Esse projeto é composto por uma série de desafios (4-1 ao 4-7) do módulo de Controle de Academia do **Bootcamp LaunchBase da Rocketseat.**
Nesses desafios praticamos os conceitos básicos da criação de um sistema de cadastro, atualização, remoção e listagem em conjunto com o uso dos verbos HTTP, todos esses foram novos conhecimentos adquiridos nesse módulo de Controle de Academia. 
* Página Inicial dos Professores e dos Alunos:
 
  <img src="https://i.imgur.com/OAmNibE.png" width="400"> <img src="https://i.imgur.com/LIrzM3l.png" width="400">
* Versão Mobile dos Professores:
[Imgur](https://i.imgur.com/SmZzxT0.png)

___
## :interrobang: Motivo

O Intuito é praticar os conhecimentos absorvidos ao longo do curso de javascript, html, nunjucks, css, servidor, banco de dados dentre outros a fim de estabelece-los e fixa-los de forma sólida aumentando o portfólio pessoal.
Nesse projeto, temos que praticar os conceitos de cadastro de dados via método Post, atualização via método Put, remoção de dados via método Delete e listagem de dados via método Get. Além  da criação de funções que filtram esses dados antes de serem mostrados na página web ou antes da inserção no banco de dados.
Não obstante, utilizamos aplicações como browser-sync e npm-run-all para a atualização e sincronização do código na web simultaneamente enquanto estiver atualizando o código , adicionando mais alguma funcionalidade ou alterando o visual, além de executarem todas ferramentas em conjunto permitindo que a partir do npm start o navegador abra automaticamente com tudo sincronizado.

* Página de visualização do Professor:
  <img src="https://i.imgur.com/DyOkFYk.png" width="800">

* Página de visualização do Aluno:
  <img src="https://i.imgur.com/JyjH5Mf.png" width="800">

* Versão Mobile do Professor e do Aluno:
 
  <img src="https://i.imgur.com/RCXrcce.png" width="300">___________<img src="https://i.imgur.com/JqYJmjV.png" width="300">

  <img src="https://i.imgur.com/RABfmJX.png" width="300">___________<img src="https://i.imgur.com/I55abpN.png" width="300">
___
## :seedling: Requisitos Mínimos

Node.js, Nunjucks, Express, Browser-sync, npm-run-all e method-override.
___
## :rocket: Tecnologias Utilizadas 

O projeto foi desenvolvido utilizando as seguintes tecnologias

- [Node.js](https://nodejs.org/en/)
- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [Nunjucks](https://mozilla.github.io/nunjucks/)

___
## :package: Como baixar e executar o projeto

  - Clonar o projeto:
```bash
  $ git clone https://github.com/Aszurar/Controle_Escolar.git
```
- Entrar na pasta do projeto:
```bash
  $ cd NomedaPasta
```
- Após instalar o Node.js, executar o npm:
```bash
  $ npm init -y
```
- Instalar o Express:
```bash
  $ npm install express
```
- Instalar o Nodemon:
```bash
  $ npm install -D nodemon  
```
- Após isso configure o script do arquivo package.json assim:
```json
  "scripts": {
      "start": "nodemon server.js"
    }
```
- Instalar o Nunjucks:
```bash
  $ npm install nunjucks
```
 - Instalar o  Browser-sync e npm-run-all:
```bash
  $ npm install browser-sync npm-run-all -D
```
 - Após isso configure o script do arquivo package.json assim:
 ```bash
   "scripts": {
    "start": "npm-run-all -p nodemon browsersync",
    "nodemon": "nodemon server.js",
    "browsersync": "browser-sync start --proxy http://localhost:5001 --files 'public,views'"
  },
```
 - Execução:
 ```bash
  $ npm start
```
- A utilização do browser-sync e npm-run-all basicamente serve para que o site seja aberto automaticamente assim que executamos o projeto, que a página na web se atualize cada veze que realizarmos alguma mudança no projeto, ou seja, a sincronia estea totalmente automática, facilitando o desenvolvimento.
- As configurações no serve.js já estão feitas para utilizarem essas ferramentas.
```json
{   
    "ignore": ["*.json"] 
}
```
- Isso previne o projeto de ficar em loop de carregamento "infinito" no navegador quando uma mudança for feita no arquivo json de dados.
___
Desenvolvido por :star2: Lucas de Lima Martins de Souza.

