## Project Title
Shopping Assistant and Dice Roll Simulation

## Description
This repository contains two Python programs:
1. **Shopping Assistant**: A program that helps users manage their shopping list and budget, providing suggestions for healthier choices.
2. **Dice Roll Simulation**: A program that simulates rolling a dice multiple times, counts the occurrences of each face, and calculates the probabilities of each outcome.

## Getting Started

### Dependencies
- Python 3.x

### Installation
1. Ensure you have Python 3.x installed on your system.

### Executing Programs
#### Shopping Assistant
1. Run the `shopping_assistant.py` script:
    ```bash
    python shopping_assistant.py
    ```
2. Follow the prompts to enter your budget and add items to your shopping list. The program will provide a summary and feedback based on your budget.

#### Dice Roll Simulation
1. Run the `dice_roll_simulation.py` script:
    ```bash
    python dice_roll_simulation.py
    ```
2. The program will simulate rolling a dice 10,000 times, count the occurrences of each face, and calculate the probabilities of each outcome.

## Contents
- `shopping_assistant.py`: Python script for the shopping assistant program.
- `dice_roll_simulation.py`: Python script for the dice roll simulation.

## Problem Statements
### Shopping Assistant
The goal of this program is to help users manage their shopping list and budget. Users can enter their budget and items (along with prices and quantities) they wish to purchase. The program will keep track of the total cost, provide suggestions for healthier options, and give feedback on whether the user is within their budget or over it.

### Dice Roll Simulation
The objective of this program is to simulate rolling a dice multiple times and analyze the results. The program will:
1. Roll a dice `n` times.
2. Count the occurrences of each face (1 through 6).
3. Calculate the probabilities of each face appearing based on the counts.

### Example Executions
#### Shopping Assistant
```python
Enter your budget: 20
Enter the item name (or 'done' when finished): apple 
Enter the price for apple : 3
Enter the quantity for apple : 4
Enter the item name (or 'done' when finished): orange
Enter the price for orange: 2
Enter the quantity for orange: 3
Enter the item name (or 'done' when finished): done

Shopping Summary:
4 x apple  at $3.00 each: $12.00
3 x orange at $2.00 each: $6.00
Total cost: $18.00
You are within your budget. You have $2.00 left.
```

#### Dice Roll Simulation
```python
Number of rolls: 10000
Face counts: {1: 1646, 2: 1701, 3: 1714, 4: 1690, 5: 1615, 6: 1634}
Probabilities: {1: 0.1646, 2: 0.1701, 3: 0.1714, 4: 0.169, 5: 0.1615, 6: 0.1634}
```

## Authors
- Saroj Raj
- [LinkedIn Profile](https://www.linkedin.com/in/saroj-raj-22831198/)

## Version History
- 0.1
    - Initial Release
