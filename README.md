# password-generator-gui
A lightweight Python desktop application built with Tkinter that generates secure, customizable random passwords and enables one-click clipboard copying using pyperclip


# Password Generator GUI

A desktop application built with Python and Tkinter that generates strong, customizable random passwords and allows one-click copying to the clipboard[cite: 1].

---

## Features

- **Custom Length Selection**: Choose password lengths ranging from 8 to 32 characters.
- **Complex Character Sets**: Includes uppercase letters, lowercase letters, digits, and special characters.
- **Guaranteed Variety**: Automatically includes at least one character from each character category when length is 4 or greater[cite: 2].
- **One-Click Clipboard Copy**: Quickly copy the generated password using the `pyperclip` module.
- **Intuitive GUI**: Lightweight and easy-to-use interface built using Tkinter[cite: 1].

---

## Tech Stack & Libraries
- **Tkinter**: GUI library (included with standard Python installations)[cite: 1].
- **random**: Standard library for randomized character selection and shuffling[cite: 1, 2].
- **string**: Standard library for character sets (letters, digits, punctuation)[cite: 1].
- **pyperclip**: Third-party library for clipboard operations[cite: 1].

---

## Getting Started

### 1. Prerequisites

Ensure you have Python installed. You will also need to install the `pyperclip` library[cite: 1].

```bash
pip install pyperclip
