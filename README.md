# Binary ↔ Decimal Converter (Java)

A simple Java console application that converts numbers between **binary** and **decimal** formats based on user input.

---

##  Features

- Convert **Binary → Decimal**
- Convert **Decimal → Binary**
- Interactive command-line menu
- Uses Java built-in conversion methods

---

## 🛠️ Technologies Used

- Java
- `java.util.Scanner`

---
SAMPLE OUTPUT
=== Binary ↔ Decimal Converter ===
1. Binary to Decimal
2. Decimal to Binary
Choose an option (1 or 2): 1
Enter a binary number: 1011
Decimal value: 11

Choose an option (1 or 2): 2
Enter a decimal number: 10
Binary value: 1010

How It Works

Binary → Decimal
Uses Integer.parseInt(binary, 2)

Decimal → Binary
Uses Integer.toBinaryString(decimal)

Future Improvements

Input validation for incorrect binary values

Loop menu for multiple conversions

Manual conversion logic (without built-in methods)

Author

Brian Kelly Ochieng
Software Engineer | Java & Full-Stack Development

