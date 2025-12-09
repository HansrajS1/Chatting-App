# Chatting App using Java Sockets

This is a simple **console-based peer-to-peer chat application** built using **Java Sockets** and **multi-threading**. It allows two or more clients to communicate over a local network (LAN) using **TCP/IP protocols**.

## Key Features

- Client-server architecture using Java `Socket` and `ServerSocket`
- Real-time message transmission using multithreading
- Handles multiple clients simultaneously
- Lightweight console interface
- Clear separation between server and client logic

---

## Technologies Used

| Component     | Stack             |
|---------------|-------------------|
| Language      | Java (JDK 8+)     |
| Networking    | Java Sockets (TCP)|
| Concurrency   | Java Threads      |
| Platform      | Cross-platform    |

---

## Project Structure

Chatting/
- Server.java
- Client.java
- README.md 

---

## How to Run

### 1. Compile the Code

```bash
javac Server.java
javac Client.java

