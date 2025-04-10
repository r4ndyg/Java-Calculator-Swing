# 🧮 Basic Calculator (Java Swing)

A stylish and functional calculator built with Java Swing, following the **MVC architecture** pattern and using `PropertyChangeListener` for reactive communication between model and view.

![Java Version](https://img.shields.io/badge/Java-17-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 🧱 Architecture

This project follows the **MVC (Model-View-Controller)** design pattern:

- **Model**: `CalculatorModel.java` – Handles all logic, data, and operations.
- **View**: `CalculatorView.java` – A modern, dark-themed interface with custom buttons.
- **Controller**: `CalculatorController.java` – Listens to user actions and triggers model updates.
- **Observer Pattern**: Uses `PropertyChangeListener` to reflect model changes in the view in real-time.

## ✅ Features

- Basic operations: `+`, `-`, `×`, `÷`
- Supports:
  - Decimal numbers
  - Percentage (`%`)
  - Sign toggle (`±`)
  - Clear (`C`)
- Error handling:
  - Division by zero
  - Invalid decimal inputs
- Clean and modern interface

## 📦 Requirements

- Java 11 or higher (Java 17 recommended)
- Any Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)


