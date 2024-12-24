# Minitalk

[![42 École](https://img.shields.io/badge/42-École-000000?style=flat&logo=42&logoColor=white)](https://42.fr)

**Minitalk** is a project from the 42 École curriculum that involves creating a simple client-server communication program using UNIX signals. This project emphasizes understanding inter-process communication (IPC) and signal handling in C.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

---

## About the Project

The **Minitalk** project involves building a client-server system where:
- The server can receive messages from a client.
- The client sends messages character by character to the server using UNIX signals (`SIGUSR1` and `SIGUSR2`).

This project enhances understanding of:
- Low-level UNIX signal handling.
- Synchronous and asynchronous communication.
- Converting and transferring data using bitwise operations.

---

## Features

- **Signal-based Communication:** Uses `SIGUSR1` and `SIGUSR2` for transferring data.
- **Message Handling:** Transmits messages from the client to the server.
- **Custom Encoding:** Each character is encoded into binary and sent bit by bit.
- **Reliable Communication:** Handles signal acknowledgment to ensure successful delivery.

---

## Getting Started

### Prerequisites
- A Unix-based operating system (Linux or macOS recommended).
- GCC or another compatible C compiler.
- Make utility.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hassan-kheireddin/minitalk.git
   ```
2. Enter the folder:
    ```bash
   cd minitalk
   ```
