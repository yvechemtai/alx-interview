# 0x08 Making Change

Welcome to the 0x08 Making Change project! This project is part of a short specialization on Algorithms using Python. The goal is to implement an algorithm to determine the fewest number of coins needed to meet a given amount total.

## Curriculum Details

**Instructor:** Carrie Ybay, Software Engineer at Holberton School

**Project Duration:** Jan 29, 2024, 6:00 AM - Feb 2, 2024, 6:00 AM

**Checker Release:** Jan 30, 2024, 6:00 AM

**Auto Review:** A review will be launched at the deadline.

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/python3`
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the PEP 8 style (version 1.7.x)
- All your files must be executable

## Tasks

### Task 0: Change comes from within (mandatory)

Given a pile of coins of different values, determine the fewest number of coins needed to meet a given amount total.

**Prototype:** `def makeChange(coins, total)`

**Return:** fewest number of coins needed to meet total

- If total is 0 or less, return 0
- If total cannot be met by any number of coins you have, return -1
- `coins` is a list of the values of the coins in your possession
- The value of a coin will always be an integer greater than 0
- You can assume you have an infinite number of each denomination of coin in the list

**Example:**

```python
makeChange([1, 2, 25], 37)  # Output: 7
makeChange([1256, 54, 48, 16, 102], 1453)  # Output: -1
```
