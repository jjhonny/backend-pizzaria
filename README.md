<h1 align="center" style="font-weight: bold;">API Pizzaria 💻</h1>

<p align="center">
 <a href="#tech">Technologies</a> • 
 <a href="#started">Getting Started</a> • 
  <a href="#routes">API Endpoints</a> •
</p>

<p align="center">
    <b>An API to control a pizzeria, being able to create orders, view order details and finalize orders.</b>
</p>

<h2 id="technologies">💻 Technologies</h2>

- NodeJs
- Express.js
- PostgreSQL
- Prisma
- JavaScript
- TypeScript
- Json Web Token
- bcryptjs
- Cors

<h2 id="started">🚀 Getting started</h2>

<h3>Prerequisites</h3>

Here you list all prerequisites necessary for running your project. For example:

- [NodeJS](https://github.com/)
- [Git 2](https://github.com)

<h3>Cloning</h3>

How to clone your project

```bash
git clone https://github.com/jjhonny/backend-pizzaria.git
```

<h3>Config .env variables</h2>

Use the `.env.example` as reference to create your configuration file `.env` with your Credentials

```yaml
DATABASE_URL="postgresql://test:test@localhost:5432/test?schema=public"
JWT_SECRET=test_secret
```

<h3>Starting</h3>

How to start your project

```bash
cd project-name
yarn
yarn dev
```

<h2 id="routes">📍 API Endpoints</h2>
 
<h3>USER</h3>
<h4 id="post-create-users">POST /users</h4>
<h4 id="post-login-users">POST /session</h4>
<h4 id="get-details-users">GET /me</h4>

<h3>CATEGORY</h3>
<h4>POST /category</h4>
<h4>GET /categories</h4>

<h3>PRODUCT</h3>
<h4>POST /product</h4>
<h4>GET /category/product</h4>

<h3>ORDER</h3>
<h4>POST /order</h4>
<h4>DELETE /order</h4>
<h4>POST /order/add</h4>
<h4>DELETE /order/remove</h4>
<h4>PUT /order/send</h4>
<h4>GET /orders</h4>
<h4>GET /order/detail</h4>
<h4>PUT /order/finish</h4>
