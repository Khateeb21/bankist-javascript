# bankist-javascript

# Bankist App

## Overview
**Bankist** is a fictional online banking application designed to showcase modern JavaScript development techniques. This app allows users to log in, view transactions, and manage their account. It focuses on the front-end aspects of creating a financial application, utilizing JavaScript for interactive features and a clean, user-friendly design.

## Features
- User login functionality
- View recent transactions
- Check balance, deposits, withdrawals, and interest
- Transfer money between accounts
- Close account functionality
- Auto logout after inactivity

## Technologies Used
- **HTML5**: For structuring the application
- **CSS3**: For styling and responsive design
- **JavaScript (ES6+)**: Core logic and interactivity
- **GitHub Pages**: Optional - Can be used to host the project demo

- ### How to interact with the project ####
- Four accounts are hardcoded and stored in array accounts variable  that holds account1 object, account2 object, account3 object4, for example

- const account1 = {
  owner: 'Jonas Schmedtmann',
  movements: [200, 450, -400, 3000, -650, -130, 70, 1300],
  interestRate: 1.2, // %
  pin: 1111,
};

const account2 = {
  owner: 'Jessica Davis',
  movements: [5000, 3400, -150, -790, -3210, -1000, 8500, -30],
  interestRate: 1.5,
  pin: 2222,
};

const account3 = {
  owner: 'Steven Thomas Williams',
  movements: [200, -200, 340, -300, -20, 50, 400, -460],
  interestRate: 0.7,
  pin: 3333,
};

const account4 = {
  owner: 'Sarah Smith',
  movements: [430, 1000, 700, 50, 90],
  interestRate: 1,
  pin: 4444,
};

const accounts = [account1, account2, account3, account4];

### to login in any of these four accounts

Use intials of any those account owner property for example Sarah Smith  her initials would be SS and type the initials in user input and password as her pin is 4444
after entering the crediantials of the following account you can easily know her bank balance if you want to close or delete this account enter her details in delete input with pin and user initial
if you want to transfer money to other account for example in my case sarah smith is logged in account 4 you have to type owner name in transfer input and value that will get deducted from your account and credited into their account 

## that all and thats how it depicts the transaction just like bank  has  this is what bankist is 

## I hope you understood project working and  the project logic  thank you



