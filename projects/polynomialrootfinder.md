---
layout: project
type: project
image: img/desmos.png
title: "Polynomial Solver and Root Finder"
date: 2023-08-01
published: true
labels:
  - Calculator
  - Technology
  - C
summary: "A program that calculates y-values and roots for a user-desfined polynomial function."
---

This project was designed as a solo programming in EE 160 course project using C, where a numerical problem needs to be solved under a set of given constraints. The user is prompted to enter the coefficients of the polynomial function (a + bx + cx<sup>2</sup> + dxsup>3</sup> + exsup>4</sup> + fsup>5</sup>) with a space between each value as well as the starting and ending x-values, and number of intervals. The program then generates a table for x-values, corresponding y-values, and any roots that are found. It also displays a total number of sign changes located on the table and lets the user decide if they want to change the search range for the table before ending the program. I divided this entire program into five versions to ensure each code runs successively, implementing an incremental development approach. 


This project aims at solving for the y-values and roots of the user-input based polynomial function of the form: a + bx + cx<sup>2</sup> + dxsup>3</sup> + exsup>4</sup> + fsup>5</sup>. In order to do so, I created a total of three source codes (project1.c, secant.c, and myfunc.c) and two header files (secant.h and myfunc.h). The program implements two functions, a secant method to find the roots of the polynomial function and a polynomial function to calculate corresponding y values. Additionally, three loops were essential for it to run successfully. One loop displays x-values, y-values, and root locations (if any) or a blank line (if no root is found). The second loop is for the secant method which finds the root of the polynomial when there is a sign change. The third loop is used to repeat the program and calculations if the user is not done. Lastly, two if statements, one to detect a sign change and trigger the secant method, and another to check if the user wants to keep calculating or finish the program, are included. 


Through this project, not only did I learn coding, but also gained a deeper understanding of incremental development approach, pseudocode, and flowchart. This approach significantly helped me ensure the foundation of this code was strong, which was crucial for identifying issues early and debugging the code effectively. The pseudocode and flowchart played a key role in keeping everything organized and guiding me in the right direction to complete the project. Additionally, breaking down the problem step by step made the entire process manageable to me. This approach taught me valuable lessons that I still continue to apply to future projects. 



**Program Output**
<img width="607" alt="output" src="https://github.com/user-attachments/assets/9fc8ef5f-cfbb-4db4-ad53-1fb9130c8b3b">


<img width="605" alt="pseudocode" src="https://github.com/user-attachments/assets/14dfb029-609a-48f3-893b-7cec3a683374">


<img width="1069" alt="flowchart" src="https://github.com/user-attachments/assets/832b4356-7cce-4f0f-836b-d69207405711">


You can learn more here at the [Polynomial Solver and Root Finder](https://github.com/ellieishii/Polynomial_Solver_and_Root_Finder).
