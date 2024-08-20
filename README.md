# Coffee Maker Project (OOPs)

This Python project simulates an advanced coffee maker machine that manages resources, processes orders, handles payments, and serves various coffee drinks. It demonstrates object-oriented programming principles and provides a user-friendly interface for ordering coffee.

![Python Badge](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)

## Features

- **Drink Menu:** Offers multiple coffee options including latte, espresso, and cappuccino.
- **Resource Management:** Tracks and manages water, milk, and coffee quantities.
- **Payment Processing:** Handles coin inputs (quarters, dimes, nickels, pennies) and calculates total amount.
- **Transaction Handling:** Verifies sufficient payment, provides change, and refunds if necessary.
- **Reporting:** Generates reports on current resource levels and total profit.
- **Machine Control:** Allows turning the coffee maker on and off.

## How to Use

1. **Start the Program:** Run `main.py` to initiate the coffee maker simulation.
2. **Order a Drink:** Enter the name of your desired coffee when prompted.
3. **Make Payment:** Follow instructions to insert coins.
4. **Receive Your Order:** If payment is successful, your coffee will be "served".
5. **Check Resources:** Type 'report' to view current resource levels and profit.
6. **Exit Program:** Type 'off' to shut down the coffee maker.

## Code Structure

The project is divided into four main Python files:

- `main.py`: The entry point of the program, orchestrating the coffee maker operations.
- `coffee_maker.py`: Manages resources and coffee making process.
- `menu.py`: Defines the drink menu and handles drink selection.
- `money_machine.py`: Processes payments and manages profit.

## Key Components

- **CoffeeMaker Class:** Handles resource management and coffee preparation.
- **MenuItem Class:** Represents individual drink options with their recipes.
- **Menu Class:** Manages the collection of available drinks.
- **MoneyMachine Class:** Processes financial transactions.

## Requirements

- Python 3.x

## Running the Project

1. Clone or download the project to your local machine.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run the script using Python:
   ```bash
   python main.py
