# Introduction to Synchronous Callbacks in JavaScript
[See assignment in Alexa.](https://alexa.bitmaker.co/wdi/may-2017/assignments/2603/latest)

## Getting Started
- Fork and clone this repository
- Try running `node main.js`. You should see the following output:
```
  The total number of transactions is: 10
  The total number of sales is: undefined
  The total number of purchases is: undefined
  The total number of cash sales is: undefined
  The total number of credit purchases is: undefined
  The unique vendors are: undefined
  The unique customers are: undefined
  The "big spenders" are: undefined
  The sum of all sales is: undefined
  The sum of all purhcases is: undefined
  The net profit is: undefined
  The most items sold in a single transaction is: undefined
  The sum of the smallest purchase is: undefined
```

- Check out the example question and its solution in `main.js`.
- Read through the questions included in `main.js`.
- Check out the structure of the `transactions` variable at the top of the file.
- Check out the breakdown of how to approach `QUESTION 01` (written in `main.js`).
- Answer and test each question in `main.js` (by running `node main.js` and checking the output) before moving on to the next one.

## Hints
- Each solution requires you to operate on the contents of the `transactions` array.
- At the very least, you will need to use the following Array methods:
  - `.filter()`
  - `.map()`
  - `.reduce()`
  - `.sort()`
- Documentation for these methods (and the other 'Array Extras') can be found here.
- Bitmaker's intro to callback functions can be found here.
