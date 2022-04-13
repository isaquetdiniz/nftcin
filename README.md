<h1 align="center">
  NFT CIn - O jogo
</h1>

<h3 align="center">
  Jogo sobre NFT desenvolvido para a disciplina de Engenharia de Software da UFPE no semeste 2021.2
</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/isaquetdiniz/nftcin">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/isaquetdiniz/nftcin">

  <img alt="GitHub" src="https://img.shields.io/github/license/isaquetdiniz/nftcin">
</p>

<p align="center">
  <a href="#-about-the-project">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Tutorial de Instalação>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">Licença</a>
</p>

## 👨🏻‍💻 Sobre o projeto

<h3>
  Escolhas
</h3>

<p>
  O que você diria se alguém te perguntasse qual a temática mais em alta no mundo da tecnologia? Provavelmente NFT. Nos últimos anos, muito é falado sobre conceitos abstratos representando elementos do cotidiano e ainda mais recentemente os NFTs vem tomado foco. Todavia, por mais que boa parte das pessoas saibam que eles existem, poucos conseguiriam explicar o que eles são ou até mesmo qual é o significado da sigla.

  Indo mais a fundo na problemática e no conhecimento sobre NFTs, não é difícil notarmos que os Non-Fungible Tokens não são um conceito novo e que, na verdade, aparecem de várias maneiras nas nossas vidas há muito tempo. Adotando a abordagem do NFT como um elemento de cultura imaterial, propomos uma forma inovadora e gameficada de entende-los de uma forma educativa e visual. 
</p>

<h3>
  O resultado
</h3>

<ul>
  <li>Link para o apk beta <a href="https://desafio-trinity-412lgvehq.vercel.app/" target="_blank">aqui</a></li>
</ul>

<h3>
  Pontos de melhoria
</h3>

<ul>
  <li>Melhoria no Design</li>
  <li>Melhoria nas Tipagens</li>
  <li>Melhoria nas mensagens de feedback</li>
  <li>Adicionar loadings</li>
  <li>Refatoração do código</li>
</ul>

## 🚀 Tecnologias

Tecnologias que utilizei para construir essa aplicação

- [Node.js](https://nodejs.org/en/)
- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Apollo](https://www.apollographql.com/)
- [TypeORM](https://typeorm.io/#/)
- [PostgreSQL](https://www.postgresql.org/)
- [ElephantSQL](https://www.elephantsql.com/)
- [Jest](https://jestjs.io/)


## 💻 Tutorial de Instalação

### Requisitos

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)


**Clone o projeto e acesse a pasta**

```bash
$ git clone https://github.com/isaquetdiniz/desafio-trinity.git && cd desafio-trinity
```

**Siga os passos*

```bash
# Navegue até a pasta do server, instale as dependências e inicie-o com:
$ cd server
$ yarn

# Para esse projeto utilizei um banco de dados que já estava deployado, o ElephantSQL. Crie uma instância para ser usada aqui e copie a url.
# Crie um .env na raiz do projeto com 

DB_TYPE=postgres
DB_URL=<sua_url>

# Agora podemos rodar o servidor com
$ yarn start

# A partir desse momento já é possível realizar querys para nossa API, se quiser abra o Insomnia e tente realizar um query:
query {
  getUsers{
    name
    id
    zipcode
  }
}

# Com o servidor rodando, podemos iniciar o nosso client. Para isso, abra um novo terminal e entre em /desafio-trinity/client
# Instale as dependências com:
$ yarn
# E inicie o Next.js com:
$ yarn dev

# Segure CTRL+<Mouse Esquerdo> em cima do link no terminal para abrir a página em seu navegador

# Prontinho, o projeto está rodando!

```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with 💜 by Isaque Diniz (itd), Pedro Manoel (pmdbma), Sofia Diniz (sdms), Vitória Pinheiro (vps3)👋
