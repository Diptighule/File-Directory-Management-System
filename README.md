# File Directory Management System

## 📌 Overview
The File Directory Management System is a menu-driven C++ application that manages file and directory entries using a **Binary Search Tree (BST)**. It allows users to add, search, delete, and display entries in alphabetical order.

## ✨ Features
- **Add Entry:** Add a new file or directory.
- **Search Entry:** Search for an entry by name.
- **Delete Entry:** Remove an existing entry.
- **Display Entries:** Display all entries in alphabetical order.
- **Duplicate Prevention:** Prevents entries with duplicate names.
- **Input Validation:** Accepts only `File` or `Directory` as entry types.

## 🛠️ Technologies Used
- Programming Language: C++
- Data Structure: Binary Search Tree (BST)
- Header Files: `iostream`, `cstring`, `iomanip`

## 📚 Concepts Used
- Classes and Objects
- Pointers and Dynamic Memory Allocation
- Binary Search Tree Operations
- Inorder Traversal
- Searching, Insertion, and Deletion

## 📂 Project Structure
```text
File-Directory-Management-System/
├── FileDirectoryManagement.cpp
├── README.md
└── .gitignore
```

## ▶️ How to Compile and Run

### Windows (using MinGW g++)
Compile the program:
```bash
g++ FileDirectoryManagement.cpp -o FileDirectoryManagement.exe
```

Run the program in PowerShell:
```powershell
.\FileDirectoryManagement.exe
```

### Linux
```bash
g++ FileDirectoryManagement.cpp -o FileDirectoryManagement
./FileDirectoryManagement
```

## 📋 Menu Options
```text
--- FILE MANAGEMENT SYSTEM ---
1. Add Entry
2. Search Entry
3. Delete Entry
4. Display Entries
0. Exit
```

