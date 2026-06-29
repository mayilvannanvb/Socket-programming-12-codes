# 🌐 Socket Programming — 12 Programs in C

> 12 complete, runnable socket programs covering TCP, UDP, file transfer, and multi-client servers.

---

## 📋 Program List

| # | Program | Protocol | Concept |
|---|---------|----------|---------|
| 01 | Basic TCP Server & Client | TCP | Connection setup, send/recv |
| 02 | Echo Server | TCP | Reflect client messages |
| 03 | Reverse String Server | TCP | Server-side string processing |
| 04 | Chat Application | TCP | Bi-directional messaging |
| 05 | File Transfer (Client→Server) | TCP | Binary file over socket |
| 06 | File Transfer (Server→Client) | TCP | Server sends file to client |
| 07 | Multi-Client Server (fork) | TCP | One process per client |
| 08 | Multi-Client Server (select) | TCP | I/O multiplexing |
| 09 | Basic UDP Server & Client | UDP | Connectionless datagram |
| 10 | UDP Echo Server | UDP | Fast round-trip messaging |
| 11 | UDP File Transfer | UDP | Datagram-based file send |
| 12 | Broadcast Server | UDP | One-to-many messaging |

---

## 🚀 How to Run

```bash
# Compile server
gcc tcp_server.c -o server

# Compile client
gcc tcp_client.c -o client

# Terminal 1 — start server
./server

# Terminal 2 — connect client
./client
```

---

## 🧠 Concepts You'll Learn

- `socket()`, `bind()`, `listen()`, `accept()`, `connect()`
- `send()`, `recv()`, `sendto()`, `recvfrom()`
- TCP vs UDP differences in practice
- `select()` for I/O multiplexing
- File transfer over network sockets

---

## 🛠️ Environment

- **OS:** Linux / Ubuntu
- **Compiler:** GCC
- **Language:** C

---

## 👨‍💻 Author

**Mayilvannan VB** — EEE Student | Network Programming Enthusiast  
📧 mayilvannanbalan@gmail.com
