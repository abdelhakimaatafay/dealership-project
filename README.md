# dealership-project
# Java Dealership

This Java program simulates a simple dealership system where users can either buy or sell a car based on certain conditions.

## How to Use

1. **Welcome Message**:
   Upon running the program, it will display a welcome message along with options for buying or selling a car.

2. **Options**:
   - Option 'a': Allows the user to buy a car.
   - Option 'b': Allows the user to sell a car.

3. **Buying a Car**:
   - If the user chooses option 'a' to buy a car, they will be prompted to input their budget.
   - If the budget is equal to or greater than $10,000, the program will indicate the availability of a Nissan Altima.
   - The user will be asked whether they have insurance and a valid license. Additionally, the program will inquire about the user's credit score.
   - Based on the provided information, the program will determine if the user is eligible to buy the car.

4. **Selling a Car**:
   - If the user selects option 'b' to sell a car, they will need to input the car's value and the selling price.
   - The program evaluates whether the dealership is interested in buying the car based on the provided values.

5. **Exiting the Program**:
   After completing the transaction or in case of an invalid option, the program will close.

## Usage Guide

1. Run the program in a Java environment.
2. Follow the prompts and input the required information as instructed.
3. Based on the conditions, the program will either complete the transaction or inform about eligibility or disinterest in the deal.

## Code Structure

- `Dealership.java` contains the main code for simulating the dealership system.
- It utilizes the `Scanner` class to take user inputs and a `switch` statement to handle different options.

## Requirements

- Java Development Kit (JDK) installed on your system to compile and run Java programs.
- A terminal or an integrated development environment (IDE) to execute the Java code.

## Note

- This program serves as a basic simulation and doesn't cover all possible scenarios or business rules that a real dealership might have.

Feel free to explore, modify, and extend this code according to your needs or use it as a starting point for a more comprehensive dealership management system.
