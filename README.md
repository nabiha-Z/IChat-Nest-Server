# IChat Server

## Description:

This is the backend server application for the real-time application built using NestJS. It follows a microservices architecture approach, utilizing distinct modules for functionalities, sockets, and authentication. And uses Mongodb Atlas for data storage

## Features:

- **Microservices Architecture:** Utilizes NestJS modules for better organization and scalability.
- **Real-Time Communication:** Implements WebSocket communication for real-time updates and interactions using gateway module.
- **Authentication:** Provides secure authentication mechanisms using NestJS guard authentication module.

## Getting Started:

1. **Clone the repository:**

```bash
git clone https://github.com/nabiha-Z/IChat-Nest-Server.git

```

2. **Install the dependencies:**

```bash
npm install
```

3. **Setup DB and env file:**

Setup your mongodb atlas cluster and paste the connection url in the .env.local.

4. **Start the server:**

```bash
npm run start:dev
```
