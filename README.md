# Simple Calculator Web App 🧮

This repository contains the code for a simple, yet visually appealing calculator web application. The application is built using HTML, CSS, and JavaScript, providing basic arithmetic operations and a dynamic, animated background.

## Features 🌟

- **Basic Arithmetic Operations**: Supports addition ➕, subtraction ➖, multiplication ✖️, division ➗, and exponentiation (^).
- **Pi Constant**: Includes a button for the mathematical constant π (pi) to ease calculations involving circles 🟢.
- **Dynamic Background**: Utilizes CSS animations to create a moving gradient background 🌈, enhancing the user interface.
- **Responsive Design**: The layout adjusts to different screen sizes 📱💻, ensuring usability across various devices.

## Structure 📂

The project is organized into three main files:

- `calculator.html`: The HTML document that structures the calculator, including the display and buttons for different operations.
- `style.css`: Contains the styling for the calculator, including the dynamic background animation and responsive design features.
- `script.js`: Implements the functionality of the calculator, handling user input, calculations, and display updates.

### HTML

The HTML file (`calculator.html`) sets up the calculator's structure, including an input field for the display and buttons for each digit, operation, and special functions like clearing the display or calculating the result.

### CSS

The CSS file (`style.css`) styles the calculator and the page background. It uses flexbox for centering the calculator on the page and grid layout for arranging the buttons. The dynamic background is created using keyframe animations and a linear gradient.

### JavaScript

The JavaScript file (`script.js`) adds functionality to the calculator. It includes functions to append digits and operations to the display, clear the display, remove the last character, and calculate the result using the `eval` function. Error handling is implemented to display an error message if the calculation fails.

## Usage 🚀

To use the calculator, simply open the `calculator.html` file in a web browser. Click on the buttons to input numbers and operations, and press the "=" button to calculate the result. Use the "C" button to clear the last entry and the "CA" button to clear the entire display.

## Note 📝

This calculator uses the JavaScript `eval` function for simplicity. However, for more complex or security-sensitive applications, consider implementing a safer evaluation method to parse and calculate expressions.

## Conclusion 🎉

This simple calculator demonstrates basic web development techniques, including HTML structure, CSS styling, and JavaScript functionality. It's a great starting point for beginners looking to understand how to build interactive web applications.
