<h1 align="center">
    <img alt="BeTheHero" title="#BeTheHero" src=".github/bethehero.svg" width="200px" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/JV-Amorim/BeTheHero_OmniStack11">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/JV-Amorim/BeTheHero_OmniStack11">
  
  <a href="https://github.com/JV-Amorim/BeTheHero_OmniStack11/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/JV-Amorim/BeTheHero_OmniStack11">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
</p>

<p align="center">
  <a href="#bethehero">BeTheHero</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#instruções">Instruções</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#notas">Notas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#licença">Licença</a>
</p>

<br>

<p align="center">
  <img alt="BeTheHero" src=".github/bethehero.png" width="100%">
</p>

## BeTheHero

O BeTheHero é um projeto que visa conectar pessoas que desejam fazer contribuições monetárias a ONG's (Organizações Não Governamentais) que precisam de ajuda. Trata-se de uma demonstração do poder da OmniStack (Node + React + React Native), stack totalmente em JavaScript. A aplicação foi desenvolvida na Semana OmniStack 11, realizada pela Rocketseat.

## Tecnologias

Abaixo são listadas as tecnologias utilizadas no desenvolvimento do BeTheHero:

- [Node.js;](https://nodejs.org/en/)
- [React;](https://reactjs.org)
- [React Native;](https://facebook.github.io/react-native/)
- [Expo.](https://expo.io/)

## Instruções

### Pré-requisitos
Antes de começar a rodar o projeto no seu computador, é necessário que realize os seguintes items:
- [Instalar o Node.js;](https://nodejs.org/en/download/)
- [Instalar o Yarn.](https://legacy.yarnpkg.com/lang/pt-br/docs/install/)

### Instalação - Backend
Para instalar as dependências e executar o servidor (modo desenvolvimento), clone o projeto em seu computador e em seguida execute:
```bash
cd backend
npm install
npm start
```

### Instalação - Web
Para iniciar o **Web** do React utilize os comandos:
```bash
cd frontend
yarn install
yarn start
```
Assim que o processo terminar, automaticamente será aberta no seu navegador a página `localhost:3000` contendo o projeto web.

### Mobile
```bash
# NÃO é preciso executar a linha de baixo caso ja tenha o Expo (CLI) instalado
yarn global add install expo-cli
cd mobile
yarn install
yarn start
```
Assim que o processo terminar, automaticamente será aberta no seu navegador a página `localhost:19002`. Conecte seu emulador, ou teste o aplicativo por `LAN`: baixe o aplicativo *Expo* da Play Store ou App Store e em seguida escaneie o código QR.

### Insomnia 
Para testar a API do BeTheHero, baixe e instale o [Insomnia](https://insomnia.rest/download/) e em seguida clique na Workspace → `Import/Export` → `Import Data` → `From File` → e selecione o arquivo `insomnia_export.json` neste repositório.

## Notas

Caso deseje saber mais sobre o desenvolvimento de projetos fullstack utilizando Node.js, React e React Native, você pode conferir um dos meus arquivos de notas, clicando [aqui](https://gist.github.com/JV-Amorim/15759e90cd7899bef10030be69fc262b).

## Licença

Esse projeto é licenciado pela MIT License. Veja a página da [licença](https://opensource.org/licenses/MIT) para detalhes.
