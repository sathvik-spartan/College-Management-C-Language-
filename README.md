# 🎓 College Management System (Console-based, C Language)

This is a simple **College Management System** written in **C language** for Windows, utilizing file handling and console UI features. It allows you to manage records of students, teachers, and staff, including operations such as **add**, **delete**, **search**, **edit**, and **view**.

## 🧰 Features

- 🔐 Password-protected access (`admin`)
- ➕ Add new records (Student, Teacher, Staff)
- 🗑️ Delete existing records by ID
- 🔍 Search staff records
- 📋 View all staff records
- ✏️ Modify existing staff records
- ❌ Exit the application gracefully

## 📁 File Structure

- `main.c` - Main source code for the College Management System
- `stf.dat` - Data file where all staff/student/teacher records are stored (created at runtime)

## 🛠️ Getting Started

### Prerequisites

- A C compiler (such as GCC)
- Windows OS (uses `windows.h` for cursor positioning)
- Command Line Interface (CLI)

### Compile and Run

```bash
gcc main.c -o college.exe
./college.exe
```

> Make sure you're running in a **Windows environment** for proper `gotoxy()` functionality.

## 🔐 Login

When prompted, enter the password:

```
Password: admin
```

> All characters will be masked with asterisks (`*`)

## ⚠️ To-Do (Suggestions)

- [ ] Implement full `searchstaff`, `viewstaff`, and `editstaff` functions
- [ ] Add record sorting and filtering options
- [ ] Migrate to cross-platform (remove `windows.h` dependencies)
- [ ] Improve password system with encryption

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

👨‍💻 Developed with love in C ❤️

