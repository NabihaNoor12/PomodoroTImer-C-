# ⏳ Pomodoro Task Manager (C++ Console App)

A fully-featured console-based Pomodoro timer built in C++ using *Object-Oriented Programming (OOP)* principles.  
It helps users manage tasks, goals, session history, and achievements — all from the terminal!

---

## 🚀 Features

- 🧠 *User Authentication* (Sign up / Login)
- ✅ *Task Management* with:
  - Priority (HIGH / MED / LOW)
  - Deadlines
  - Remaining Sessions
- ⏲ *Pomodoro Timer* (Traditional & Custom)
  - Pause / Resume / Stop support
  - Motivational quotes
  - Colored progress bar
- 📜 *Session History*
  - View past sessions with timestamps
- 🎯 *Goal Tracking*
  - Set and complete daily goals
  - Mark goals as achieved
- 🏆 *Achievements System*
  - Earn XP, level up, and unlock ranks
- 📅 *Schedule View*
  - View sorted tasks by deadline
- 🎨 *Colorized Console UI*
  - Green headings, red/yellow/orange priorities, pink quotes

---

## 🧩 Technologies Used

- C++17 (or later)
- chrono, thread, fstream, conio.h, and more
- ANSI Escape Codes for terminal colors
- File-based persistent storage

---


---

## 🛠 Build Instructions

### 🔧 Requirements
- C++ compiler (e.g., g++, MSVC)
- Command line / terminal

### 🧪 Compile
```bash
g++ -std=c++17 -o pomodoro main.cpp
