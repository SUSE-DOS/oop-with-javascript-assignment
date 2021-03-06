
[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# OOP with JavaScript: Assignment

## Make an ATM

For this exercise you will be creating an ATM class.

It will have the following properties:

- `type` (e.g., "checking"), which should be determined by some input
- `money`, which should start out as `0`

It should have the following methods:

- `withdraw`, which should decrease the amount of money by some input
- `deposit`, which should increase the amount of money by some input
- `showBalance`, which should print the amount of money in the bank to the console.

The `Atm` class also has a `transactionHistory` property which keeps track of the withdrawals and deposits made to the account. Using an `Array` for this might be a good idea.

Also, make sure to indicate whether the transaction increased or decreased the amount of money in the bank by using `console.log`.