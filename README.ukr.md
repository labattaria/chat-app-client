**Читати іншою мовою: [Українська](README.ukr.md), [English](README.md).**

# Chat app client

---

[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](#)
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](#)
[![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](#)
[![GraphQL](https://img.shields.io/badge/GraphQl-E10098?style=for-the-badge&logo=graphql&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)
[![ApolloGraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)](#)
[![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)](#)

Це клієнтська частина React/GraphQL/Apollo, створена та налаштована для додатку **Chat Application**

Клієнтський застосунок (як і серверний) підтримує протокол WebSocket, який забезпечує двосторонній зв’язок між клієнтом і сервером через одне постійне TCP-з’єднання.

Цей клієнтський застосунок також використовує GraphQL Subscriptions, що разом із протоколом WebSocket дає нам можливість отримувати свіжі дані миттєво, без окремих запитів.

Як клієнт, так і сервер можуть надсилати повідомлення один одному одночасно, що робить це ідеальним для застосунків у реальному часі.

Це лише частина всього додатку, друга частина (сервер) знаходиться в цьому репо: [Chat server](https://github.com/labattaria/chat-app-server)

Застосунок у цьому репозиторії працює з сервером, який розміщено за адресою: [https://render.com](https://render.com), за цією URL-адресою: [https://chat-app-server-0qdt.onrender.com/graphql](https://chat-app-server-0qdt.onrender.com/graphql)

Але ви можете використовувати цей сервер вручну на своєму локальному комп’ютері

## Залежностi, якi використовуються:

- **Vite** - Швидкий і сучасний інструмент збірки, який забезпечує дуже швидку та гарячу заміну модулів (HMR) для розробки, оптимізований для фреймворків
- **React** - Бібліотека, що використовується для створення користувацьких інтерфейсів, особливо для односторінкових застосунків, де потрібен швидкий та інтерактивний досвід
- **GraphQL** - Основна бібліотека GraphQL
- **Graphql-subscriptions** – Дозволяє реалізувати GraphQL-підписки для надсилання даних у реальному часі клієнтам
- **Graphql-ws** – Реалізація транспорту WebSocket для GraphQL-підписок
- **JWT (JSON Web Token)** - Компактний, безпечний для URL формат токена, який використовується для безпечної передачі інформації між сторонами. Зазвичай застосовується для автентифікації та авторизації у вебзастосунках
- **Apollo-client** - Бібліотека для керування станом, спеціально розроблена для роботи з GraphQL API. Вона допомагає вашому застосунку ефективно отримувати, кешувати та керувати даними з GraphQL-сервера

Повний список залежностей можна знайти у файлі **package.json**

---

## Вміст

- [Встановлення](#Встановлення)
- [Використання](#Використання)

### Встановлення

1. Склонуйте репозиторій:

```shell
git clone https://github.com/labattaria/chat-app-client.git
```

2. Встановіть залежності проекту:

```shell
cd chat-app-client
npm install
```

### Usage

Start the dev-server using the following command:

```shell
npm start
```

Server will be located at **http://localhost:3000/chat-app-client/**
