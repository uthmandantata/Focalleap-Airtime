# Focalleap Airtime App

Welcome to the Focalleap Airtime App README! This web-based application allows users to perform various operations related to their airtime balance and data balance. The app is implemented using HTML and JavaScript, and it utilizes prompts and alerts for user interaction.

## How to Use

1. **Getting Started**: Open the `index.html` file in a web browser to launch the Focalleap Airtime App.

2. **Usage**: Upon launching the app, you'll be presented with a prompt that allows you to select from the following options:

   - Enter `*123#` to Check Balance: This option displays your current airtime and data balances.
   - Enter `*100#` to Buy Airtime: Enter the amount you want to add to your airtime balance.
   - Enter `*101#` to Borrow Airtime: Borrow airtime if your balance is not exhausted.
   - Enter `*` to Exit: This option allows you to exit the app.

3. **Invalid Inputs**: If you provide an invalid input other than `*123#`, `*100#`, `*101#`, or `*`, an alert will notify you of the invalid input and prompt you again.

4. **Exiting the App**: When you're done using the app, you can select option `*` to exit. You will receive a thank you message.

## Code Overview

The code is contained within the `<script>` tag in the HTML file. Here's a brief overview of the key components:

- `airtime_balance` and `data_balance`: Variables to store the airtime and data balances, respectively.
- `while (true)`: An infinite loop that keeps the app running until the user chooses to exit.

The loop presents users with options and uses the `prompt` function for input and the `alert` function for output.

- Checking Balance: Option `*123#` displays the current airtime and data balances using an alert.
- Buying Airtime: Option `*100#` prompts the user to enter an amount of airtime to buy, which is then added to the airtime balance.
- Borrowing Airtime: Option `*101#` prompts the user to enter an amount of airtime to borrow if their balance is not exhausted.
- Exiting: Option `*` exits the app and displays a thank you message.

## Note

This app serves as a basic example of how a simple airtime-related application can be implemented using HTML and JavaScript. However, it lacks advanced features and security measures required for real-world applications. For actual usage, more robust security measures and validation checks should be implemented.

Feel free to explore and modify the code to enhance your understanding of web development and user interactions!

---
