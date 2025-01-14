# WebSocket Chat
A simple real-time chat application using WebSockets with [Node.js](https://nodejs.org/en) and [Express](https://expressjs.com). The app features dynamic message handling and a modern design powered by [Pico.css](https://picocss.com).

## Getting Started
### Installation
1. Clone the repository:
```bash
git clone https://github.com/magicalmonke/websocket-chat.git
cd websocket-chat
```
2. Install dependencies:
```bash
npm install
```

### Usage
To start the application:
```bash
node index.js
```
The chat server will run at http://localhost:3000 by default.

## Docker Deployment
1. Build the Docker image:
```bash
docker build -t websocket-chat .
```
2. Run the container:
```bash
docker run -d -p 3000:3000 websocket-chat
```