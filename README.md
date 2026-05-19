# A Simple MERN Stack Application

## Run the Application with Docker Compose

### Prerequisites

- Install Docker
- Install Docker Compose

Verify installation:

```bash
docker --version
docker compose version
```

### Start the Application

From the project root, run:

```bash
docker compose up --build
```

> **Note:**  
> You can add the `-d` option to run the containers in detached mode.

Example:

```bash
docker compose up -d --build
```

### Stop the Application

```bash
docker compose down
```

---

## Run the Application Locally Without Docker

### Prerequisites

- Install Node.js
- Install npm

### Start the Backend Server

```bash
cd mern/server
npm install
npm start
```

### Start the Frontend Client

```bash
cd mern/client
npm install
npm run dev
```

---

## Application Preview

<img width="1790" alt="Application Screenshot" src="https://github.com/user-attachments/assets/f414230b-8bd6-4393-b8de-6a10444a8dfd">
