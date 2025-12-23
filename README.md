# 🗂️ Mini Version Control System (Git Internals)

## 📌 Overview
This project is a **simplified version control system inspired by Git**, built to understand how Git works internally.  
It focuses on core concepts such as **repository initialization, file tracking, commits, hashing, and history management**.

The goal of this project is not to recreate Git completely, but to **learn and implement the fundamental building blocks** behind modern version control systems.

---

## 🎯 Objectives
- Understand how Git tracks files internally
- Learn how commits are created and stored
- Explore hashing and directory-based object storage
- Gain hands-on experience with file systems and system-level programming

---

## ⚙️ Features Implemented

- **Repository Initialization (`init`)**
  - Creates a hidden directory to store version control metadata
  - Sets up required folder structure

- **File Staging (`add`)**
  - Tracks selected files for the next commit
  - Stores file snapshots using hash-based identifiers

- **Commit Creation (`commit`)**
  - Generates a unique commit using content hashing
  - Saves commit metadata and file references

- **Commit History (`log`)**
  - Displays the history of commits
  - Shows commit identifiers and messages in chronological order

---

## 🧠 Core Concepts Covered

- File system traversal  
- Content-based hashing  
- Snapshot-based versioning  
- Commit metadata management  
- Basic understanding of Git object storage  

This project strengthened my understanding of how Git efficiently manages changes over time.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Concepts Used:**  
  - File handling  
  - Hashing  
  - Directory structures  
  - Command-line style workflows  

---

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/slietian/Mini-Version-Control-System-Git-Internals-
   cd mini-version-control-system
Initialize repository

python vcs.py init


Add files

python vcs.py add <filename>


Commit changes

python vcs.py commit "commit message"


View commit history

python vcs.py log

📘 Learning Outcomes

Gained a deeper understanding of Git internals

Learned how version control systems manage file changes

Improved problem-solving and system design skills

Strengthened confidence in system-level programming concepts

🔮 Future Enhancements

Branch support

File diff comparison

Checkout to previous commits

Improved command-line interface

📄 Disclaimer

This project is built for learning and educational purposes to understand Git internals.
It is not intended to replace Git or be used in production environments.

🙌 Acknowledgement

Inspired by studying Git internals and system design concepts.
