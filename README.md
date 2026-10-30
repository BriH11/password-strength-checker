# 🔐 Password Strength Checker

A Java command-line program that rates how strong a password is and explains exactly what makes it weak and how to improve it.

## Project Goal

Many people create weak or reused passwords without realizing how easy they are to crack, and most websites just say "weak" without explaining why. This project checks a password, gives it a strength rating, and gives specific tips to make it stronger. I'm building it because I'm interested in cybersecurity and want to understand how password security actually works.

## MVP Scope (Version 1.0)

- **Length check:** flags passwords shorter than 8 characters
- **Character variety check:** checks for uppercase letters, lowercase letters, numbers, and symbols
- **Common password check:** compares the password against a list of common passwords
- **Strength rating:** outputs **Weak**, **Medium**, or **Strong**
- **Explanations and tips:** explains each problem found and how to fix it
- **Input loop:** checks as many passwords as you want until you type `quit`

## Future Plans (Version 2.0+)

- Pattern detection (repeated characters like `aaa`, sequences like `1234` or `abcd`)
- Estimated time to crack the password
- Strong password generator
- Hidden password input while typing
- Flagging personal info (like a name or birth year) in the password

## Tech Stack

- **Language:** Java
- **Built-in Java classes:** `Scanner`, `Character`, `BufferedReader` / `FileReader`, `HashSet`
- **External libraries:** none for the MVP (JUnit planned for testing)
- **Data storage:** `data/common-passwords.txt`, a plain text list of common passwords (from SecLists)
- **External data sources:** none; the program runs fully offline
- **Tools:** Git, GitHub, IntelliJ / VS Code, terminal

> 🔒 **Privacy note:** Passwords you check are never saved. They're only checked in memory while the program runs.

## Project Structure

```
password-strength-checker/
├── src/          # Java source code
├── tests/        # Test files
├── data/         # common-passwords.txt
├── docs/         # Eisenhower Matrix and System Diagram
└── README.md
```

## Design Docs

- [Eisenhower Matrix](docs/eisenhower-matrix.pdf)
- [System Diagram](docs/system-diagram.png)

## How to Run

*Coming soon: run instructions will be added once the program is built.*

## Author

Briana Harvey, Purdue University
