---
layout: project
type: project
image: img/desmos.png
title: "Polynomial Solver and Root Finder"
date: 2023-08-02
published: true
labels:
  - Calculator
  - Technology
  - C
summary: "A program that calculates y-values and roots for a user-desfined polynomial function."
---

This project was designed as a solo programming in EE 160 course project using C, where a numerical problem needs to be solved under a set of given constraints. The user is prompted to enter the coefficients of the polynomial function (a + bx + cx^2 + dx^3 + ex^4 + fx^5) with a space between each value as well as the starting and ending x-values, and number of intervals. The program then generates a table for x-values, corresponding y-values, and any roots that are found. It also displays a total number of sign changes located on the table and lets the user decide if they want to change the search range for the table before ending the program. I divided this entire program into five versions to ensure each code runs successively, implementing an incremental development approach. 


This project aims at solving for the y-values and roots of the user-input based polynomial function of the form: a + bx + cx^2 + dx^3 + ex^4 + fx^5. In order to do so, I created a total of three source codes (project1.c, secant.c, and myfunc.c) and two header files (secant.h and myfunc.h). The program implements two functions, a secant method to find the roots of the polynomial function and a polynomial function to calculate corresponding y values. Additionally, three loops were essential for it to run successfully. One loop displays x-values, y-values, and root locations (if any) or a blank line (if no root is found). The second loop is for the secant method which finds the root of the polynomial when there is a sign change. The third loop is used to repeat the program and calculations if the user is not done. Lastly, two if statements, one to detect a sign change and trigger the secant method, and another to check if the user wants to keep calculating or finish the program, are included. 


Through this project, not only did I learn coding, but also gained a deeper understanding of incremental development approach, pseudo code, and flowchart. This approach significantly helped me ensure the foundation of this code was strong, which was crucial for identifying issues early and debugging the code effectively. The pseudo code and flowchart played a key role in keeping everything organized and guiding me in the right direction to complete the project. Additionally, breaking down the problem step by step made the entire process manageable to me. This approach taught me valuable lessons that I still continue to apply to future projects. 

**<Flow Chart>**
img/flowchart.png

You can learn more at the [Polynomial Solver and Root Finder](https://manoa.hawaii.edu/news/article.php?aId=2857).
