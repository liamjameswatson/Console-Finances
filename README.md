# Console-Finances

Analysing financial records

## Description

In this project, I was given a financial dataset, and tasked with writing an algorithm using javascript, that can analysize the profits/losses of a company.

The algorithm had to give the following information:

- The total number of months included in the dataset.
- The net total amount of Profit/Losses over the entire period.
- The average of the changes in Profit/Losses over the entire period.
- The greatest increase in profits (date and amount) over the entire period.
- The greatest decrease in losses (date and amount) over the entire period.

To acheive this, I used a series of for loops.

- The first thing I did was seperate the months, and the numbers into two arrays, this made it easy to analyise each array.
- I got the total, average, greatest and lowest numbers in the number array, and then linked it back to the month array with the strict equality operator.
- To round up the results, I used the toFixed() method.

## Usage

To see the results, open the website on a web browser. Right click on the page and select inspect from the dropdown menu, and go to the console tab. You should see the results, as shown in the screenshot below.

## Screenshot

![Screenshot](./assets/images/screenshot%20of%20console-finances.png)

## The website

This site can be found at https://liamjameswatson.github.io/Console-Finances/

## License

MIT License (Please refer to [LICENSE](/LICENSE) in the repo.)
