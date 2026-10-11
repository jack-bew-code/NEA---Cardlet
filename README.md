# Cardlet (A-Level Computer Science NEA Project)

> **Note:** This repository contains my original A-Level Computer Science Non-Exam Assessment (NEA) codebase, preserved exactly as submitted for assessment purposes.

Cardlet is a Python desktop flashcard application designed to help students create, organise, and review custom study sets.

## Overview & Features
- **User Authentication System:** User signup and login interface utilising custom hashing and salting logic.
- **Sorting & Data Handling:** Implements a custom Merge Sort algorithm for user verification alongside SQLite database integration.
- **GUI Application:** Built with Tkinter and `ttkthemes` using a multi-frame object-oriented architecture.
- **Flashcard Engine:** Create, review, flip, and navigate through flashcard sets.

## Tech Stack
- **Language:** Python 3
- **GUI:** Tkinter / `ttkthemes` (`superhero` theme)
- **Database:** SQLite3

---

## Retrospective & Known Limitations
*As this repository is an unedited snapshot of an academic project, it reflects my skills at the time of submission:*

- **Hardcoded File Paths:** Uses absolute local paths (e.g., `C:/Users/...`) for the database and asset loading rather than relative directory paths.
- **Custom Security:** Features a custom demonstration hashing function created for the project requirements rather than production-grade cryptographic libraries (like `bcrypt` or `hashlib.pbkdf2`).
- **Database Scope:** Uses global connection objects rather than context-managed database sessions.
