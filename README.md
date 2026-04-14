# Websockets Live Sports Dashboard Backend

A real-time sports dashboard backend built to master **WebSockets** using the native `ws` library.

This project was created as a learning exercise to deeply understand how WebSockets work under the hood — from connection handling and broadcasting to managing multiple clients in a live environment.

### Project Purpose

The main goal was to gain strong hands-on experience with native WebSockets using the `ws` library.

I focused on:
- Establishing persistent bidirectional connections
- Broadcasting live updates to multiple connected clients
- Handling connection events (open, message, close, error)
- Managing rooms/topics for different matches
- Clean server architecture with Express + PostgreSQL integration

### Tech Stack

- **Node.js** + **Express.js**
- **WebSockets** using the native [`ws`](https://github.com/websockets/ws) library
- **PostgreSQL** with **Drizzle ORM**

### What I Learned

- How WebSockets differ from traditional HTTP (full-duplex vs request-response)
- The WebSocket handshake process and frame-based communication
- Efficient broadcasting to all clients or specific rooms
- Handling connection lifecycle and graceful disconnection
- Combining Express HTTP routes with WebSocket upgrade handling
- Real-time data flow patterns.

This project gave me solid confidence in implementing real-time features using native WebSockets without relying on higher-level libraries like Socket.io.

### Special Thanks

Huge credit and thanks to **JavaScript Mastery** for creating such a high-quality and practical WebSocket course. The course was excellent at breaking down complex real-time concepts into clear, actionable steps.

### How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/verweyruan/websockets-sports-dashboard-backend.git

# 2. Install dependencies
cd websockets-sports-dashboard-backend
npm install

# 3. Run the server
npm run dev
