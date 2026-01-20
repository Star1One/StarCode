


#  React Calculator App

## Introduction

The React Calculator App is a web application.

This App provides a user-friendly interface and It supports basic arithmetic operations, decimal numbers, formatted output, and intuitive input handling similar to a real calculator.

---

### 🔢 Features

- Addition, Subtraction, Multiplication, Division

- Decimal number support with precision control

- Smart input handling (prevents invalid sequences)

- Automatic number formatting

- Continue calculation after =

- Delete last input & reset calculator

---

### 🛠 Installation & Setup

1. Clone the repository

2. Navigate to the project folder

3. Install dependencies
```terminal
  npm install
```

4. Start the development server
```terminal
  npm run dev
```

4. Open app in your browser

---

### 💡 How It Works

- User input is stored as a raw expression array

- The display shows a formatted version of the numbers

- When = is pressed:

    - The expression is parsed into numbers and operators

    - The calculation runs left-to-right

-   The result is rounded to avoid floating-point errors

- After calculation:

-   Pressing a number starts a new calculation

-   Pressing an operator continues from the result

---

### ⚠️ Known Limitations

Operations are evaluated left-to-right

```
  2 + 3 × 4 = 20
```
---

### 📄 License

This project is open-source and available under the MIT License.

---

### 📸 Screenshots

![Weather App Screenshot](images/calc.jpg)

