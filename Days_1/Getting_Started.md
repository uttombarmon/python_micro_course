# Getting Started — Python Micro Course ✅

## Introduction

Welcome! This short guide helps you get set up for the **Python Micro Course** and documents the repository's **first program**. Follow the steps below to install Python, set up a working environment on Windows, and run the first sample program.

---

## Prerequisites 🔧

- A computer with Windows (instructions here emphasize Windows, but macOS/Linux steps are similar).
- Internet access to download Python and optional tools.
- Basic familiarity with opening a terminal (PowerShell or CMD) and editing a text file.

---

## Install Python (Windows) 🐍

1. Check whether Python is already installed:

```powershell
python --version
# or
py --version
```

2. If Python is not installed, download it from https://www.python.org/downloads/ or install via the Microsoft Store.

   - During installation, check **Add Python to PATH** if prompted. This makes `python` available from the terminal.

3. Confirm pip is available:

```powershell
pip --version
```

4. Optional recommended tools:
   - Visual Studio Code: https://code.visualstudio.com/
   - Git: https://git-scm.com/
   - VS Code extensions: **Python** (Microsoft), **Pylance**, and **Code Runner** (optional).

> Note: On Windows you can use the `py` launcher (e.g., `py -3`) to be explicit about Python 3.

---

## Create and use a virtual environment (recommended) 🌐

From the project root (where this repository is located):

```powershell
# Create the venv
python -m venv .venv

# Activate the venv (PowerShell)
.\.venv\Scripts\Activate.ps1

# OR (Command Prompt)
.\.venv\Scripts\activate

# Upgrade pip
pip install --upgrade pip
```

Using a virtual environment isolates project dependencies and is best practice for Python projects.

---

## First program: `Days_1/firstProgram.py` 📝

This repository includes a minimal first program at `Days_1/firstProgram.py`:

```python
print("Start First Program")
```

### What it does

- Prints the message **Start First Program** to the terminal.

### How to run

From the project root, run:

```powershell
python Days_1/firstProgram.py
# or on Windows if you use the py launcher
py -3 Days_1/firstProgram.py
```

Expected output:

```
Start First Program
```

### Run in VS Code

- Open the folder in VS Code.
- Open `Days_1/firstProgram.py` and press the green Run button, or run the script in the integrated terminal.
- To debug, add a breakpoint and use the built-in debugger.

---

## Common issues & troubleshooting ⚠️

- `python` not found: ensure Python is installed and added to PATH.
- Wrong working directory: run from the repository root or provide the full path to the script.
- Indentation or syntax errors: check the code for typos and proper indentation.

---

## Suggested exercises ✅

1. Modify `Days_1/firstProgram.py` to print your name.
2. Ask the user for input and greet them:

```python
name = input("What's your name? ")
print(f"Hello, {name}!")
```

3. Add a small calculation (e.g., print the result of 6 \* 7).

---

## Resources & links 💡

- Official Python docs: https://docs.python.org/3/
- VS Code Python: https://code.visualstudio.com/docs/python/python-tutorial

---

If you'd like, I can:

- Open this file in the editor, or
- Update `Days_1/firstProgram.py` with a tiny example that prompts for input.

Tell me which next step you'd prefer.
