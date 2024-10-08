<h1 align="center">
  <img src="doc/icon.png" width="50px" alt="icon" >
  <br>
  pizza shop
  <br>
</h1>

<p align="center">
  <img alt="GitHub Language Count" src="https://img.shields.io/github/languages/count/jhonbergmann/pizza-shop" />
  <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/jhonbergmann/pizza-shop" />
</p>

<p align="center">Dashboard for establishment management and order control in the iFood style.</p>

<p align="center">
  <img src="doc/illustration.png" alt="illustration" >
</p>

## 📦 Tech Stack

- React
- ElysiaJS
- Drizzle
- Typescript

## 🔩 Installation

### web

To install and run the project locally, follow these steps:

1. Install [**Yarn**](https://yarnpkg.com/) on your computer
1. Clone the repository `git clone https://github.com/jhonbergmann/pizza-shop`
1. Navigate to the project directory: `cd pizza-shop/web`
1. Install the dependencies: `yarn install`

### api

1. Install [**Bun**](https://bun.sh/) on your computer
1. Install [**Docker**](https://www.docker.com/) on your computer
1. Clone the repository `git clone https://github.com/jhonbergmann/pizza-shop`
1. Navigate to the project directory: `cd pizza-shop/api`
1. Install the dependencies: `bun i`

## ⚙️ Usage

### web

Start the development server: 

1. Run: `yarn dev`

### api

Start the development server: 

1. Run: `docker compose up -d`
1. Run: `bun migrate`
1. Run: `bun seed`
1. Run: `bun dev`

## 📝 License

[MIT © Jhonatan Bergmann](https://github.com/jhonbergmann/pizza-shop/web/blob/main/LICENSE)
