# 🔐 Encrypted Chat Application (RSA + Python Sockets)

This is a simple end-to-end encrypted chat application built with **Python sockets** and **RSA encryption**.  
Two users can securely exchange messages over a TCP connection using public/private key pairs.

---

## 🚀 Features
- Peer-to-peer encrypted messaging
- RSA public/private key exchange
- Supports **host** and **client** modes
- Multithreaded (send & receive simultaneously)

---

## 🛠️ Requirements
- Python 3.8+
- Install dependencies:
```bash
pip install rsa


1. Host (Server)
python main.py


When prompted:

Do you want to host (1) or to connect (2)? 1


The host will start listening on:

IP: 192.168.56.1
Port: 23809

2. Client

Open another terminal (or another machine on the same LAN):

python main.py

When prompted:

Do you want to host (1) or to connect (2)? 2


****The client will connect to the host’s IP and port.
