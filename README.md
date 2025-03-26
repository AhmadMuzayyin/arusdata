# ArusdataJS Project

Lightweight real-time messaging library for JavaScript applications.

## Project Structure

This monorepo contains all components of the ArusdataJS platform:

- [`client/`](./client) - Core JavaScript client library
- [`server/`](./server) - WebSocket server implementation
- [`demo/chat`](./demo/chat) - Example chat application
- [`landing/`](./landing) - Website and documentation

## Quick Start

### Server Setup

```bash
# Install dependencies
cd server
npm install

# Start the server
npm start

# Install dependencies
cd demo/chat
npm install

# Start the demo
npm start

# Install dependencies
cd landing
npm install

# Start landing page
npm start
```

## Client Library
The ArusdataJS client library can be installed via NPM:

```html
<script src="https://cdn.jsdelivr.net/npm/arusdata@0.1.0/dist/arusdata.min.js"></script>
```

## Features

WebSocket-based real-time communication
Channel-based architecture
Event-driven messaging
Support for private channels
Presence channels for user status tracking
Automatic reconnection
Zero dependencies
Tiny footprint (~10KB gzipped)

## Documentation
For full documentation, visit https://arusdatajs.com or see the documentation in the landing/docs directory.
License
MIT