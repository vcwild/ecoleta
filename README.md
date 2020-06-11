<h1 align="center">
  <img alt="Ecoleta" src="https://raw.githubusercontent.com/vcwild/ecoleta/84cbe382772348e52a9ad6dcfcf6cc1c73d12499/web/src/assets/logo.svg" width="250px" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vcwild/ecoleta">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/vcwild/ecoleta">

  <a href="https://github.com/maykon-oliveira/nlw-1/blob/master/LICENSE.md">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  <a>
</p>

## :memo: Projeto

Elaborado na semana do meio ambiente e com foco ecológico, o projeto apresenta como finalidade elencar empresas de coleta de resíduos a usuários desse serviço, oferecendo uma plataforma de fácil acesso tanto para encontrar pontos de coleta quanto para o cadastro de novas entidades.


## :house: Web

<h1 align="center">
    <img alt="Ecoleta title=#web Front-end" src="https://github.com/maykon-oliveira/nlw-1/raw/master/.github/web.gif" />
</h1>

## :iphone: Mobile

<h1 align="center">
    <img alt="Ecoleta Mobile" title=#mobile src="https://github.com/maykon-oliveira/nlw-1/raw/master/.github/mobile.gif" />
</h1>

## :hammer: Tecnologias

Desenvolvimento:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [API do IBGE para consumo do endereço](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-UFs-estadosGet)
- [Upload de imagens](react-dropzone)
- [celebrate](https://github.com/arb/celebrate)

Testes:

- [SINON.JS](https://sinonjs.org/)
- [Chai](https://www.chaijs.com/)
- [Mocha](https://mochajs.org/)

## :wrench: Instalação

```bash
# Clone este repositório
$ git clone git@github.com:vcwild/ecoleta.git

# Navegue até a pasta server e execute os seguintes comandos:
$ yarn knex:migrate
$ yarn knex:seed
$ yarn start

# Depois disso, entre na pasta web e execute o comando:
$ yarn start

# E finalmente, entre na pasta mobile e execunte o comando:
$ expo start

# Observações:
- Não esqueça de mudar a baseURL no arquivo api.ts das pastas web e mobile para o ip da sua máquina
```

## 🐳 Deploy no docker

```bash
# Na pasta raiz do projeto
$ sudo docker-compose up -d
```

## :scroll: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

<h1 align="right">
  <img alt="Ecoleta" title="#delicinha" src="https://raw.githubusercontent.com/vcwild/ecoleta/84cbe382772348e52a9ad6dcfcf6cc1c73d12499/web/src/assets/home-background.svg" width="250px" />
</h1>

<h6 align="right">
Animações por <a href="https://www.github.com/maykon-oliveira/">Maykon Oliveira</a>
</h6>
