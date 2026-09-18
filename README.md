# 🔐 Custom Password Generator CLI

A lightweight, interactive command-line application built in Python that generates customizable, secure passwords. The tool features custom ASCII art banners, user-defined security parameters, a password strength evaluator, and low-level keypress exit handling.

---

## ✨ Features

- **Interactive UI**: Custom small ASCII banners generated dynamically using `art.text2art`.
- **Customizable Security Options**: Toggle uppercase letters, digits, and special characters on or off.
- **Guaranteed Character Inclusion**: Ensures at least one character from every selected category is included.
- **Password Strength Evaluator**: Rates generated passwords as *Weak*, *Moderate*, *Strong*, or *Very Strong* based on chosen criteria.
- **Keypress Exit Handling**: Uses `msvcrt` on Windows (with cross-platform fallbacks) to exit smoothly on a `0` keypress.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **`random` & `string`**: Core logic for character selection and shuffling.
- **`art`**: Terminal ASCII art generation.
- **`msvcrt` / `sys`**: Platform-specific console I/O handling.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed on your system. Install required third-party packages:

```bash
pip install art
