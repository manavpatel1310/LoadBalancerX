# **LoadBalancerX**

## **About**

**LoadBalancerX** is a **multi-server load balancing system** designed to efficiently distribute client requests across multiple servers. This project leverages **advanced socket programming** and **process management techniques** in C, running on **Debian Linux OS**, ensuring optimal **resource utilization** and enhanced **system performance**.

---

## **Key Features**

- **Efficient Load Balancing** – Dynamically distributes client requests across multiple servers to **prevent overload** and **optimize performance**.
- **Advanced Socket Programming** – Uses **TCP/IP protocols** for reliable communication between clients and servers.
- **Concurrent Request Handling** – Implements **multi-process strategies** to manage **multiple client connections simultaneously**.
- **Recursive Directory Scanning** – Enhances **file management** by efficiently scanning directories for requested resources.
- **File Attribute Manipulation** – Provides advanced **file attribute handling**, improving overall system responsiveness.

---

## **Technologies Used**

- **Programming Language** – C  
- **Operating System** – Debian Linux  
- **Networking Protocols** – TCP/IP  

---

## **Getting Started**

### **Prerequisites**

- **Debian-based Linux OS**
- **GCC Compiler**

---

### **Installation**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/manavpatel1310/LoadBalancerX.git

2. **Navigate to the project directory:**
   ```bash
   cd RequestRouter
   ```
3. **Compile the source code:**
   ```bash
   gcc -o request_router clientw24.c mirror1.c mirror2.c serverw24.c
   ```

### Usage

1. **Start the server:**
   ```bash
   ./serverw24
   ```
2. **Start the mirrors:**
   ```bash
   ./mirror1
   ./mirror2
   ```
3. **Connect clients to the server using the client program:**
   ```bash
   ./clientw24
   ```

### Project Structure

```
RequestRouter/
├── .vscode/
├── .DS_Store
├── clientw24.c
├── mirror1.c
├── mirror2.c
├── serverw24.c
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.
