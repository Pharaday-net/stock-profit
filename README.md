# Coding Challenge: Maximum Stock Profit

## Problem Statement

You are given an array of integers `prices`, where each element represents the price of a stock on a given day. The index of the array represents the day number (starting from 0). You want to maximize your profit by choosing a single day to buy one stock and choosing a different day **in the future** to sell that stock.

**Write a function that returns the maximum profit you can achieve from this transaction. If no profit is possible, return `0`.**

### Example 1
```
Input: prices = [7, 1, 5, 3, 6, 4]
Output: 5
Explanation: Buy on day 1 (price = 1) and sell on day 4 (price = 6), profit = 6 - 1 = 5.
```

### Example 2
```
Input: prices = [7, 6, 4, 3, 1]
Output: 0
Explanation: No profit is possible since the price decreases every day.
```

Constraints:

- 1 <= prices.length <= 10^5
- 0 <= prices[i] <= 10^4
