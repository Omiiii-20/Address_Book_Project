# Address Book (C Project)

## Author

Om Bidikar

---

## About the Project

This project is a command-line Address Book application written in C.
It allows users to store, manage, and organize contact details efficiently using file handling.

The application supports operations like adding, viewing, editing, deleting, and searching contacts.

---

## Features

* Add new contacts
* View all stored contacts
* Edit existing contact details
* Delete contacts
* Search contacts by name

---

## 📁 Project Structure

Address_Book_Project/

Source Files:

* src/ (main.c, contact.c, file.c, functions.c)

Header Files:

* include/ (contact.h, file.h, function.h)

Data Files:

* data/ (contacts.txt)

Documentation:

* README.md

---

## ⚙️ How to Compile

```bash id="6rkpj0"
gcc src/*.c -o addressbook
```

---

## ▶️ How to Run

```bash id="9y0hx5"
./addressbook
```

---

## 🧪 Functionalities

1. Add Contact
2. View Contacts
3. Edit Contact
4. Delete Contact
5. Search Contact

---

## 🧠 Concepts Used

* Structures in C
* File Handling
* String Manipulation
* Modular Programming

---

## ⚠️ Limitations

* Command-line interface only
* Data stored in text file (no database)
* Limited input validation

---

## 💡 How It Works

The program stores contact details in a text file (`contacts.txt`) and performs operations like add, edit, delete, and search using file handling techniques.

---

## 📘 License

This project is for learning purposes.
