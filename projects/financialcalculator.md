---
layout: project
type: project
image: img/financialcalculator.png
title: "Financial Calculator"
date: 2024-01-20
published: true
labels:
  - Calculator
  - Algorithm
  - Java
summary: "A program that calculates the monthly account balance over a year based on user inputs for the initial amount, yearly interest rate, and monthly payment."
---


This Java program serves as a financial calculator that allows users to input their initial account balance, yearly interest rate, and monthly payment amount through a graphical user interface (GUI). The program is designed to provide an intuitive experience, enabling users to easily enter their financial details into formatted text fields. Once the inputs are received, the program processes them to convert the yearly interest rate into a monthly rate, ensuring that the calculations are accurate and reflect real-world financial scenarios.

The core functionality of the program lies in its ability to compute the monthly account balance for a year using the formula 
a * (1 + (i / 100)) + c, where a is the current balance, i is the monthly interest rate, and c is the monthly payment. The calculation is performed in a loop that iterates twelve times, once for each month, updating the balance based on the interest accrued and the contributions made. The results are formatted to two decimal places for clarity, reflecting typical financial reporting standards.

Finally, the computed monthly balances are displayed in a text area within the GUI, allowing users to easily track how their account evolves over time. This visualization not only aids in understanding the impact of regular payments and interest on savings but also promotes financial literacy by demonstrating the long-term benefits of saving and investing. Overall, this project combines programming skills with practical financial knowledge, making it a valuable tool for users seeking to manage their finances effectively.

Here is the code for computeOutput method, which uses a loop to calculate and display the monthly account balances.

private static String computeOutputs(double amount, double interest, double payment) {
    StringBuilder result = new StringBuilder();
    
    for (int month = 0; month <= 12; month++) {
        result.append(String.format("%.2f\n", amount));
        amount = amount * (1 + (interest / 100)) + payment;
    }
    
    return result.toString();
}


<img width="400px" class="rounded pe-4" src="../img/calculator.jpg">









You can learn more here at the [Financial Calculator](https://github.com/ellieishii/Financial Calculator).
