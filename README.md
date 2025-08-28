# CPP-00

This repository contains solutions for the first day of the 42 Network's C++ modules. It is designed to introduce fundamental concepts of C++ programming through hands-on exercises. Each exercise is contained in its own directory and demonstrates basic language features, object-oriented programming, and project structure.

## Table of Contents

- [ex00 - Megaphone](#ex00---megaphone)
- [ex01 - PhoneBook](#ex01---phonebook)
- [Build & Run](#build--run)
- [Requirements](#requirements)
- [License](#license)

---

## ex00 - Megaphone

A simple C++ program that takes a single argument and outputs it in uppercase, simulating a "megaphone".  
If the argument count is incorrect, it will notify the user.

**Usage:**
```sh
./megaphone "your message"
```

## ex01 - PhoneBook

A basic PhoneBook application that allows users to add, search, and view contacts. The phonebook can store up to 8 contacts. When the limit is reached, new contacts overwrite the oldest ones.

**Features:**
- Add a new contact (first name, last name, nickname, phone number, and dark secret).
- Search for contacts and display a summary table.
- Display full details of a selected contact by index.
- Input validation and friendly prompts.

**Commands:**
- `ADD`: Add a new contact.
- `SEARCH`: Display all contacts and select one to view details.
- `EXIT`: Exit the application.

**Usage:**
```sh
./PhoneBook
```
Follow the on-screen instructions to use the commands.

---

## Build & Run

To build the projects, navigate to the respective exercise folder and run `make`:

```sh
cd ex00
make
./megaphone "Hello World!"

cd ../ex01
make
./PhoneBook
```

## Requirements

- C++98 standard
- GNU Make
- g++ compiler

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

*Created as part of the 42 Network C++ piscine.*
