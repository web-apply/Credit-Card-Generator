# Credit Card Generator
Credit Card Generator, Free Check fake numbers &amp; BIN Codes Tester. You can test your credit card and create virtual new credit card for use payment apis & codes.

Luhn's algorithm, named for this algorithm
Hans Peter Luhn, who developed it. This algorithm, based on the established 1950s, is not really new.

In everyday life, the numbers of credit cards we use in the physical environment, or online, are not arbitrarily determined. Card numbers are specified in a specific standard frame. Here we call this standard the luhn algorithm.

Luhn's algorithm
working principle is as follows;

Take our sample card number 4242-4242-4242-4242.

We will perform our control in 3 steps.

## First step:
The figures in the double digit are collected.

For 2,2,2,2,2,2,2,2

2 + 2 + 2 + 2 + 2 + 2 + 2 + 2 = 16

## Second step:
We multiply the numbers in a single dummy by 2 and add up the digits.

For 4,4,4,4,4,4,4,4

4 x 2 = 8 & gt; 8
4 x 2 = 8 & gt; 8
4 x 2 = 8 & gt; 8
4 x 2 = 8 & gt; 8
4 x 2 = 8 & gt; 8
4 x 2 = 8 & gt; 8
4 x 2 = 8 & gt; 8
4 x 2 = 8 & gt; 8

In this example, we take only 8 because the result is a single digit.

8 + 8 + 8 + 8 + 8 + 8 + 8 + 8 = 64

## Step three:
We sum up the two total results. If the result is exactly the 10th, in other words if mod10 is zero, we can say that the credit card number is valid.

16 + 64 = 80 (the card number is valid since 10 is the full rank). thanks
https://github.com/web-apply/Credit-Card-Generator-With-Money
Demo:  ![Credit [Credit Card Generator With Money]([https://creditcardgenerator.money/](https://creditcardgenerator.money/)) Card Generator With Money]([Credit Card Generator With Money]())



