# **Credit Card Validator** 

This program verifies the validity of a credit card number using the Luhn algorithm.

![creditcard](https://cdn.dribbble.com/users/1143699/screenshots/3444736/cc-loader.gif)

It calculates the checksum by summing the processed digits of the card number, alternating between doubling every second digit and adding single digits. If the total is divisible by 10, the card number is considered valid; otherwise, it is invalid.