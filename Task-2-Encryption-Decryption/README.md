# Basic Encryption and Decryption Tool

A Python-based application that encrypts and decrypts text using the Caesar Cipher technique.

## Overview

This project implements a basic encryption and decryption system using the Caesar Cipher. It accepts a text message and a numerical shift key, transforms alphabetic characters to produce encrypted text, and reverses the process to recover the original message.

## Features

- Accepts text input from the user.
- Takes a numerical shift key.
- Encrypts text using the Caesar Cipher.
- Decrypts the encrypted message using the same key.
- Preserves spaces, punctuation, and letter case.
- Displays the original, encrypted, and decrypted text.

## Technologies Used

- Python 3
- Python built-in functions

## Encryption Technique

The project uses the **Caesar Cipher**, a substitution cipher in which each alphabetic character is shifted by a fixed number of positions.

For example, with a shift key of 3:

| Original | Encrypted |
|---|---|
| A | D |
| B | E |
| C | F |

The same shift key is used in reverse to decrypt the message.

## Project Structure

```text
encryption-decryption-toolkit/
│
├── src/
│   ├── __init__.py
│   └── encryption.py
│
├── docs/
│   └── requirements.md
│
├── .gitignore
├── README.md
└── requirements.txt
```

## How to Run

Clone the repository:

```bash
git clone https://github.com/dikshaasudha29/encryption-decryption-toolkit.git
```

Navigate to the project directory:

```bash
cd encryption-decryption-toolkit
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Run the program:

```bash
python src/encryption.py
```

## Concepts Demonstrated

- String handling
- ASCII character conversion
- Conditional statements and loops
- Shift keys
- Modular arithmetic
- Basic cryptography concepts

## Future Improvements

- Implement additional encryption techniques.
- Add a menu-driven interface.
- Improve input validation.
- Support file-based encryption and decryption.