# AnnoyingPopup

A Python-based desktop popup restriction and time-management application created for educational purposes using Tkinter and SQLite.

---

## Overview

AnnoyingPopup is a Python desktop application designed to simulate a restriction or reminder system using popup windows, fullscreen warnings, timers, and user-based controls.

The project was created as a learning exercise for:

- Python GUI programming
- SQLite database integration
- Timers and threading
- Desktop application behavior
- User account management
- Startup automation
- Packaging Python applications into executables

---

## Features

- Fullscreen warning window
- Popup spam warning system
- Timer countdown functionality
- SQLite-based user management
- Parent and child account logic
- Startup launch support
- Randomized popup behavior
- GUI built with Tkinter
- Executable (.exe) support using PyInstaller

---

## Technologies Used

- Python
- Tkinter
- SQLite3
- Threading
- PyInstaller
- Windows Registry (startup support)

---

# IMPORTANT DISCLAIMER

This project was created strictly for:

- Educational purposes
- GUI experimentation
- Desktop application practice
- Database integration practice
- Python learning

This software is NOT intended to:

- Harm devices
- Lock users out of systems maliciously
- Disrupt or damage computers
- Act as ransomware or malware
- Bypass user consent

The source code is publicly available for transparency and educational review.

Users are responsible for how they run or modify the application.

---

# Safety Precautions

Before running the application:

## Recommended Precautions

- Test the application on your own computer only
- Use a virtual machine if experimenting with startup behavior
- Read the source code before executing
- Avoid enabling startup execution unless necessary
- Keep emergency exit controls enabled
- Avoid setting excessively aggressive popup intervals

## Recommended Emergency Exit

Example emergency keybind:

```python
root.bind("<Control-Shift-Q>", lambda e: root.destroy())
```

This allows the application window to be closed safely.

---

# Installation Guide

## 1. Install Python

Download Python from:

https://www.python.org/downloads/

During installation:

- Enable "Add Python to PATH"

---

## 2. Clone or Download the Repository

Using Git:

```bash
git clone https://github.com/YOUR_USERNAME/AnnoyingPopup.git
cd AnnoyingPopup
```

Or download the ZIP manually from GitHub.

---

## 3. Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 4. Run the Application

```bash
python main.py
```

---

# Creating an Executable (.exe)

This project can be converted into a standalone Windows executable using PyInstaller.

## Install PyInstaller

```bash
pip install pyinstaller
```

## Build the Executable

```bash
pyinstaller --onefile --windowed main.py
```

Generated executable will appear inside:

```text
dist/
```

---

# Project Structure

```text
AnnoyingPopup/
│
├── main.py
├── README.md
├── requirements.txt
├── .gitignore
├── assets/
├── database/
├── screenshots/
└── dist/
```

---

# Database Information

The application uses SQLite for local data storage.

Example database usage:

- User accounts
- Timers
- Restrictions
- Session data

Database files are excluded from GitHub uploads using:

```gitignore
*.db
```

---

# GitHub Upload Notes

Before uploading:

## Recommended Files to Upload

- Python source files
- README.md
- requirements.txt
- screenshots
- assets/icons

## Files Recommended to Ignore

- __pycache__/
- dist/
- build/
- *.db
- *.spec
- IDE folders

---

# Known Limitations

- Windows-focused behavior
- Tkinter UI styling limitations
- Popup spam may become excessive with low delay values
- Startup behavior depends on Windows configuration
- Fullscreen mode may behave differently on multi-monitor systems

---

# Future Improvements

Possible future updates:

- Improved UI design
- Object-oriented refactor
- Better settings system
- Theme customization
- Safer popup management
- Better parent controls
- Logging system
- Export/import settings
- Cross-platform support

---

# Educational Topics Demonstrated

This project demonstrates:

- GUI programming
- Event handling
- Timers and scheduling
- Threading
- SQLite databases
- File system management
- Windows startup automation
- Python packaging

---

# Contribution

Contributions, suggestions, and improvements are welcome.

If contributing:

- Keep code readable
- Avoid malicious functionality
- Add comments when necessary
- Test changes before submitting

---

# License

This project is licensed under the MIT License.

---

# Author

Created by Mark Stephen Delos Reyes.

---

# Screenshots

Add screenshots inside the `screenshots/` folder and reference them below.

Example:

```markdown
![Preview](screenshots/preview.png)
```

---

# Notes

This project is intended as a learning experience and portfolio project.

Always use software responsibly.

