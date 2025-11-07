# TCP-Based Multi-User Chat System

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A command-line chat application built with Python's built-in socket and threading modules, featuring multi-channel support and private messaging.

## 🌟 Features

- 🆔 Unique nickname identification
- 🌐 Multi-channel communication
- 🔒 Private messaging between users (`/pm` command)
- 🧵 Threaded server handles multiple clients concurrently
- 📨 Real-time message broadcasting within channels
- 🚪 Graceful connection handling and disconnection
- 💻 Simple and intuitive command-line interface

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- No external dependencies required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/TCP-Based-Multi-User-Chat-System.git
cd TCP-Based-Multi-User-Chat-System
```

## 🛠️ Usage

### Starting the Server
1. Run the server on your machine:
```bash
python3 server.py
```
   - The server will start on `0.0.0.0:5555` by default
   - To change the port, modify the `PORT` constant in `server.py`

### Connecting Clients
1. Run the client on any machine in the network:
```bash
python3 client.py
```
2. When prompted, enter the server's IP address
3. Choose a unique nickname when asked
4. Enter the channel you want to join

### Available Commands
- Type any message to broadcast to your current channel
- `/pm <nickname> <message>` - Send a private message to a specific user
- `/quit` - Disconnect from the server

## 📂 Project Structure

- `server.py` - Handles client connections and message routing
- `client.py` - Client-side interface for connecting to the chat server
- `README.md` - This documentation file

## 📝 Notes
- The server supports multiple channels that users can join
- Users in different channels won't see each other's messages
- Private messages are end-to-end between the sender and recipient
- The server handles client disconnections gracefully

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


