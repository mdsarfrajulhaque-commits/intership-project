# Digital Bill Generator

## Project Overview
The Digital Bill Generator is a Python-based application designed to simplify the supermarket billing process. It allows users to enter item names and their prices, automatically calculates the total bill amount, and generates a digital receipt in image format.

This project demonstrates the practical use of Python programming concepts such as loops, conditional statements, exception handling, lists, and image processing.

## Features
- **Item Entry:** Allows users to enter multiple item names and prices.
- **Automatic Calculation:** Calculates the total bill amount automatically.
- **Input Validation:** Handles invalid price inputs using exception handling.
- **Digital Receipt Generation:** Creates a properly formatted supermarket bill as an image.
- **Receipt Saving:** Saves the generated receipt as a PNG image.
- **User-Friendly Interface:** Provides simple text-based interaction.

## Technologies Used
- Python
- Google Colab
- PIL (Python Imaging Library)
- IPython Display

## How It Works
1. The program welcomes the user to the supermarket billing system.
2. The user enters the item name and its price.
3. The program adds each item to the shopping list.
4. The total bill amount is calculated automatically.
5. The user types `done` to finish adding items.
6. A formatted digital receipt is generated and displayed.
7. The receipt is saved as a PNG image.

## Installation and Execution

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new Python notebook.
3. Copy and paste the project source code.
4. Run the code.
5. Enter item names and prices.
6. Type `done` to generate the final receipt.

## Output
The program generates a digital supermarket receipt containing:
- Supermarket bill heading
- List of purchased items
- Individual item prices
- Total amount due
- Thank-you message

The receipt is saved in PNG format as `Supermarket_Receipt.png`.

## Learning Outcomes
Through this project, I learned how to:
- Implement loops and conditional statements in Python.
- Store and manage data using lists.
- Perform calculations using user inputs.
- Handle errors using exception handling.
- Generate and display images using the PIL library.

## Future Improvements
- Add quantity and item-wise price calculation.
- Include GST and discount calculations.
- Add date and time to the receipt.
- Develop a graphical user interface.
- Store billing records for future reference.

## Conclusion
The Digital Bill Generator is a simple and practical Python project that demonstrates how programming can automate everyday billing activities. It provides an easy way to calculate shopping expenses and generate digital receipts.
