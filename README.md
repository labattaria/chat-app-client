**Read in another language: [Українська](README.ukr.md), [English](README.md).**

# Chat app client

---

[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](#)
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](#)
[![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](#)
[![GraphQL](https://img.shields.io/badge/GraphQl-E10098?style=for-the-badge&logo=graphql&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)
[![ApolloGraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)](#)
[![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)](#)

This is the React/GraphQL/Apollo client, designed and configured for the **Chat Application**

The client application (as well as the server app) supports the WebSocket protocol, which enables bidirectional communication between the client and server through a single persistent TCP connection.

This client-app also uses GraphQL Subscriptions, which, together with the WebSocket protocol, allows us to receive fresh data instantly without making separate requests.

Both the client and server can send messages to each other simultaneously, making it ideal for real-time applications.

This client-side app is only part of the application, the second part (the server) is located at this repo: [Chat server](https://github.com/labattaria/chat-app-server)

The app in this repo works with the server hosted at [https://render.com](https://render.com), hosting public URL: [https://chat-app-server-0qdt.onrender.com/graphql](https://chat-app-server-0qdt.onrender.com/graphql)

But you can use this app manually on your local machine

## Used dependencies:

- **Vite** - A fast and modern build tool that provides lightning-fast hot module replacement (HMR) for development, optimized for frameworks
- **React** - Library used for building user interfaces, particularly for single-page applications where you need a fast, interactive experience
- **GraphQL** - Core GraphQL library
- **Graphql-subscriptions** – Enables implementing GraphQL subscriptions to push real-time data to clients
- **Graphql-ws** – WebSocket transport implementation for GraphQL subscriptions
- **JWT (JSON Web Token)** - A compact, URL-safe token format used for securely transmitting information between parties. Commonly used for authentication and authorization in web applications
- **Apollo-client** - State management library specifically designed for working with GraphQL APIs. It helps your app fetch, cache, and manage data from a GraphQL server efficiently

The full list of dependencies can be found in the **package.json** file

---

## Contents

- [Installation](#installation)
- [Usage](#usage)

### Installation

1. Clone the repository:

```shell
git clone https://github.com/labattaria/chat-app-client.git
```

2. Install project dependencies:

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
