---
title: "LC-3 Calculator"
excerpt: "LC-3 Assembly Implementation of Five-Function Calculator"
collection: portfolio
---

This calculator was coded using the LC3 assembly language, which is similar to RISC. It can perform addition, subtraction, multiplication, division, and exponent calculations.
The input syntax is in Reverse Polish Notation (a.k.a. postfix notation), and the output format is in hexcode. 
Calculation order can be configured using parentheses, and it can detect syntax errors such as division by zero. 

<img src='/images/proj4_1.png'>
The image above shows a sample calculation. The left-hand window is the terminal.
93-24-/ is the postfix notation for 6 / -2. The result, -3, is FFFD in hex. 


Link to Project: https://github.com/darwonkim720/LC-3_Calculator

## Key Takeaways: 
- Using flowcharts to outline code before implementation
- Implementing subroutines for more concise code
- Identifying and implementing solutions for edge cases (i.e. 2^0=1, 3 x -2 = -3 x 2)
