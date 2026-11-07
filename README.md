# Console Finances

A JavaScript analysis of a company's monthly profit and loss records covering 86 months, from January 2010 to February 2017. The results print to the browser console.

**Live page:** https://temioye.github.io/console-finances/ (open your browser's developer console to see the output)

<img width="813" alt="Console output showing the financial analysis" src="https://user-images.githubusercontent.com/117649696/225433406-96f55c70-944d-4f6b-9f35-10b51cf21330.png">

## What it calculates

- Total number of months in the dataset
- Net total of profits and losses over the whole period
- Average month-on-month change
- Greatest increase in profits (date and amount)
- Greatest decrease in profits (date and amount)

## Built with

- Plain JavaScript, using loops over a nested array

## Run it locally

1. Clone the repo
2. Open `index.html` in your browser and open the developer console (F12)

## What I learned

- Working through a dataset step by step to produce summary statistics
- Comparing each record with the one before it to measure change over time
- Writing readable, explicit logic that's easy to check by hand
