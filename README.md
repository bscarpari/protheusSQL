<a name="readme-top"></a>

<img alt="Header" width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=7B61FF&height=180&section=header&text=Protheus%20SQL&fontSize=42&fontColor=ffffff&fontAlignY=32&desc=React%20%C2%B7%20Node.js%20%C2%B7%20PostgreSQL&descAlignY=52&descSize=16"/>

<h3 align="center">An interactive platform for learning and practising SQL</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/bscarpari/">
    <img alt="Made by" src="https://img.shields.io/badge/-Bruno%20Scarpari-blue?style=flat-square&logo=Linkedin&logoColor=white">
  </a>

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/bscarpari/protheusSQL?style=flat-square">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/bscarpari/protheusSQL?style=flat-square">

  <a href="https://github.com/bscarpari/protheusSQL/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/bscarpari/protheusSQL?style=flat-square">
  </a>

  <img alt="License" src="https://img.shields.io/github/license/bscarpari/protheusSQL?style=flat-square">
</p>

<p align="center">
  <a href="#-about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-features">Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting started</a>
</p>

<img alt="Protheus SQL demo" width="100%" src="https://raw.githubusercontent.com/bscarpari/protheusSQL/main/protheus_demo.png">

---

## 🌐 About

A web tool for learning SQL by writing it. Users run **real queries against a fictional database** and see the results immediately, instead of reading syntax in the abstract.

Built as the final project for the Technical Course in Computer Science at **IFSul — Campus Gravataí**.

---

## ✨ Features

| Feature | What it does |
|---------|--------------|
| Query editor | Executes SQL against a sample database and returns results in real time |
| Reference panel | Syntax guide and common functions, shown alongside the editor where they're needed |
| Dashboard | Tracks the user's progress and practice history |
| Calendar | Organizes study sessions |
| Forum | Lets users share solutions and discuss approaches |

---

## 🚀 Technologies

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frontend** — React, Tailwind CSS
**Backend** — Node.js, Express, Sequelize
**Database** — PostgreSQL

---

## 💻 Getting started

**Requirements**

| Tool | Version |
|------|---------|
| Node.js | >= 16.x |
| PostgreSQL | >= 13 |

**1. Clone the repository**

```bash
git clone https://github.com/bscarpari/protheusSQL.git
cd protheusSQL
```

**2. Install dependencies**

<!-- PLACEHOLDER: confirmar os nomes reais das pastas (client/server? frontend/backend?) -->

```bash
cd server && npm install
cd ../client && npm install
```

**3. Configure the database connection**

<!-- PLACEHOLDER: informar o caminho real do arquivo de config e as variáveis
     que ele espera. Exemplo abaixo — substituir pelos nomes verdadeiros. -->

Create a `.env` file in the `server` folder:

```env
DB_HOST=localhost
DB_PORT=5432
DB_NAME=protheus
DB_USER=your_user
DB_PASSWORD=your_password
```

**4. Create the database structure**

<!-- PLACEHOLDER: comando real de migrations/seed -->

```bash
cd server
npx sequelize-cli db:migrate
```

**5. Run the project**

<!-- PLACEHOLDER: comando real da raiz -->

```bash
npm run dev
```

The application will be available at [http://localhost:3000](http://localhost:3000).

---

## 📄 License

[MIT](https://choosealicense.com/licenses/mit/)

---

<p align="center">
  Made with 💜 by <a href="https://www.linkedin.com/in/bscarpari/">Bruno Scarpari</a> ·
  <a href="https://github.com/bscarpari">GitHub</a> ·
  <a href="mailto:bscarpari.dev@gmail.com">Email</a>
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<img alt="Footer" width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=7B61FF&height=100&section=footer"/>
