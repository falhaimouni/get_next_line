# 📄 get_next_line

> A low-level line-reading function in C that returns one line at a time from a file descriptor, handling buffering and memory management efficiently.

---

## 📌 Project Overview

**get_next_line** is a project from the 42 School curriculum that challenges students to implement a function that reads a file line by line, returning each line with every call. It teaches careful memory handling, buffer management, and working with file descriptors.

The function must be able to:
- Read from any valid file descriptor
- Return one line per call (including the newline `\n`)
- Handle multiple file descriptors simultaneously

---

## 🎯 Objectives

- Understand file reading via `read()`  
- Manage dynamic memory and buffers  
- Create an efficient buffer system that handles incomplete lines  
- Maintain a separate buffer per file descriptor  
- Return lines **without leaks or crashes**

---

## 🛠️ Function Prototype

```c
char *get_next_line(int fd);
```
## 📥 Installation & Usage

### Clone the Repository

```bash
git clone https://github.com/yourusername/get_next_line.git
cd get_next_line
