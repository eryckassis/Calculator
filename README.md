# Scientific Calculator (Python)

A robust and user-friendly scientific calculator developed in Python, featuring a professional command-line interface. This project demonstrates strong programming logic, modular code structure, comprehensive error handling, and supports a wide range of mathematical operations. It is ideal for students, developers, and anyone seeking a functional calculator in the terminal.

---

## Features

- **Basic Operations:** Addition, subtraction, multiplication, division, exponentiation.
- **Advanced Mathematics:** Square root, power, factorial, logarithms (base 10 and natural).
- **Trigonometry:** Sine, cosine, tangent (input in degrees).
- **Input Validation:** Prevents invalid entries and division by zero.
- **Clean CLI Interface:** Easy-to-navigate, clear, numbered menu.
- **Extensible:** Modular code structure for adding new features with ease.

---

## Interface Preview

```shell
===== Scientific Calculator =====
Select operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Power (x^y)
6. Square Root (√x)
7. Logarithm (log base 10)
8. Natural Logarithm (ln)
9. Sine (sin)
10. Cosine (cos)
11. Tangent (tan)
12. Factorial (n!)
13. Exit

Choose an operation (1-13): 1
Enter first number: 10
Enter second number: 20
Result: 10.0 + 20.0 = 30.0
Press Enter to continue...
```

---

## How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/scientific-calculator-python.git
    cd scientific-calculator-python
    ```
2. **Run the calculator:**
    ```bash
    python scientific_calculator.py
    ```
3. **Follow the on-screen menu to perform calculations.**  
   Enter the corresponding number for the desired operation and provide your values.

---

## Project Structure

```plaintext
scientific-calculator-python/
│
├── scientific_calculator.py   # Main calculator script
└── README.md                  # Project documentation
```

---

## Technologies

- [Python 3.x](https://www.python.org/)
- Standard Library (`math` module)

---

## Code Quality Highlights

- **Functional Modularity:** Each operation is managed by a dedicated function for clarity and maintainability.
- **Error Handling:** Comprehensive `try/except` blocks ensure safe user input and mathematical operations.
- **User Experience:** Clear prompts, error messages, and result presentation.
- **Extensible Design:** Easily add more scientific or statistical functions as needed.

---

## Operation Examples

| Operation          | Example Input     | Example Output           |
|--------------------|------------------|-------------------------|
| Addition           | 5, 7             | 5 + 7 = 12              |
| Square Root        | 9                | √9 = 3                  |
| Logarithm (base 10)| 100              | log₁₀(100) = 2          |
| Sine               | 90 (degrees)     | sin(90°) = 1            |

---

## Contributing

Contributions are welcome! Feel free to fork the repository, enhance the features, or suggest improvements via pull requests.

---

## License

This project is released under the [MIT License](LICENSE).

---

<p align="center">
  Developed with a focus on clean code and usability.
</p>
