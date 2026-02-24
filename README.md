# 🏥 Hospital Management System

> A Python-based console application to streamline hospital operations — managing patients, doctors, and appointments efficiently.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## 📖 About the Project

The **Hospital Management System** is a Python-based application designed to simplify and automate the day-to-day operations of a hospital. It allows staff to manage patient records, doctor information, and appointment scheduling — all from a simple, interactive console interface.

This project was built as part of my B.Tech (AI & Data Science) learning journey to practice Python programming, data handling, and real-world problem solving.

---

## ✅ Features

- 📋 **Patient Management** — Add, view, update, and delete patient records
- 👨‍⚕️ **Doctor Management** — Maintain a list of available doctors and their specializations
- 📅 **Appointment Scheduling** — Book and manage appointments between patients and doctors
- 🔍 **Search Functionality** — Search for patients or doctors by name or ID
- 📁 **Data Persistence** — Patient and doctor data is stored and retrieved across sessions
- 🖥️ **Console-Based Interface** — Simple menu-driven interface for easy navigation

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python 3.x** | Core programming language |
| **File Handling / CSV** | Data storage and retrieval |
| **OOP Concepts** | Structured code using classes and objects |
| **VS Code** | Development environment |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- Python 3.x — [Download here](https://www.python.org/downloads/)
- Git — [Download here](https://git-scm.com/)

You can verify your Python installation by running:

```bash
python --version
```

---

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/Akash-Dhanwate/python-project.git
```

2. **Navigate into the project directory**

```bash
cd python-project
```

3. **No additional dependencies required** — this project uses Python's built-in libraries only.

---

### Running the Application

```bash
python main.py
```

Once launched, you will see a menu like this:

```
========== Hospital Management System ==========
1. Add Patient
2. View All Patients
3. Search Patient
4. Add Doctor
5. Book Appointment
6. View Appointments
7. Exit
================================================
Enter your choice:
```

Follow the on-screen prompts to navigate through the system.

---

## 📁 Project Structure

```
python-project/
│
├── main.py              # Main entry point of the application
├── patient.py           # Patient class and related functions
├── doctor.py            # Doctor class and related functions
├── appointment.py       # Appointment scheduling logic
├── data/
│   ├── patients.csv     # Stored patient records
│   └── appointments.csv # Stored appointment records
└── README.md            # Project documentation
```

> **Note:** File/folder names may vary depending on the actual structure of the repository.

---

## 🔮 Future Improvements

Here are features planned for future versions of this project:

- [ ] **GUI Interface** — Build a graphical interface using Tkinter or PyQt
- [ ] **Database Integration** — Replace CSV/file storage with MySQL or SQLite for better scalability
- [ ] **Billing System** — Add invoice generation and payment tracking for patients
- [ ] **Authentication** — Role-based login system for Admin, Doctor, and Receptionist
- [ ] **Report Generation** — Export patient and appointment reports as PDF
- [ ] **Web Version** — Rebuild the system as a web app using Flask or Django

---

## 👤 Author

**Akash Dhanwate**

- 🎓 B.Tech — Artificial Intelligence & Data Science
- 💼 LinkedIn: [linkedin.com/in/4kashdhanwate](https://www.linkedin.com/in/4kashdhanwate)
- 🐙 GitHub: [github.com/Akash-Dhanwate](https://github.com/Akash-Dhanwate)
- 📷 Instagram: [instagram.com/ur_4kash](https://www.instagram.com/ur_4kash)

---

> ⭐ If you found this project useful or interesting, feel free to **star the repository** — it means a lot!

---

*Built with 💙 as part of my Python learning journey.*
