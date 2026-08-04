# 🐧 Linux Fundamentals

This directory contains my Linux learning notes as part of my **DevOps Learning Journey**. It covers the basic concepts of Linux, its architecture, boot process, and essential components required for DevOps.

---

## 📖 Topics Covered

- Linux Overview
- Linux Kernel
- Linux Shell
- Linux Bootloader
- Linux System Architecture

---

## 🐧 What is Linux?

Linux is an **open-source operating system** widely used for:

- ☁️ Cloud Computing
- 🌐 Networking
- 🖥️ Servers
- 🔐 Cybersecurity
- 🚀 DevOps

---

# 🧠 Linux Kernel

The **Linux Kernel** is the core component of the Linux operating system.

### Responsibilities

- Process Management
- Memory Management
- Device Management
- File System Management
- Hardware Communication

---

# 💻 Linux Shell

The **Shell** is a command-line interpreter that acts as a bridge between the user and the Linux Kernel.

### Responsibilities

- Accepts user commands
- Passes commands to the kernel
- Displays command output

---

# 🔄 How Linux Works

```text
User
  │
  ▼
Shell
  │
  ▼
Kernel
  │
  ▼
Hardware
```

### Workflow

1. User enters a command.
2. Shell interprets the command.
3. Kernel processes the request.
4. Hardware performs the task.
5. Output is displayed to the user.

---

# ⚡ Bootloader

A **Bootloader** is a small program responsible for loading the operating system into memory during startup.

## Boot Process

```text
Power On
    │
    ▼
 BIOS / UEFI
    │
    ▼
 Bootloader (GRUB)
    │
    ▼
 Linux Kernel
    │
    ▼
 Operating System Starts
```

### Why Bootloader is Important

- Loads the Linux Kernel into RAM.
- Starts the operating system.
- Allows selecting between multiple operating systems.

### Most Common Bootloader

**GRUB (GRand Unified Bootloader)**

---

# 🏗️ Linux System Architecture

```text
+---------------------------+
|           User            |
+---------------------------+
              │
              ▼
+---------------------------+
|      Application Layer    |
+---------------------------+
              │
              ▼
+---------------------------+
|          Shell            |
+---------------------------+
              │
              ▼
+---------------------------+
|         Linux Kernel      |
+---------------------------+
              │
              ▼
+---------------------------+
|        Hardware           |
| CPU • RAM • Disk • NIC    |
+---------------------------+
```

### Architecture Overview

| Layer | Description |
|--------|-------------|
| User | Interacts with the operating system |
| Applications | Software such as Git, Docker, VS Code, etc. |
| Shell | Executes user commands |
| Kernel | Manages hardware and system resources |
| Hardware | Physical components of the computer |

---

# 📚 References

- Linux Documentation
- Linux Manual Pages (`man`)
- GNU Project Documentation

---

## 🎯 Learning Goal

Understand the Linux operating system and build a strong foundation for:

- DevOps
- Docker
- Kubernetes
- Ansible
- Terraform
- Cloud Computing

---

⭐ These notes are part of my **DevOps Learning Journey**.