---
layout: project
type: project
image: img/recursivemethods.png
title: "Recursive Methods for Number System Conversion and Fibonacci Sequence Analysis"
date: 2024-02-17
published: true
labels:
  - Recursion
  - Rumtime
  - Java
summary: "A program that implements recursive methods to convert decimal numbers into ternary and hexadecimal bases, calculates the first twelve Fibonacci numbers, and analyzes runtime performance for various Fibonacci sequence computations.."
---

This Java program implements several recursive methods to work with number systems and sequences. There were basic notes given but I was responsible for completing the program, and to ensure it works correctly. The first section of the program converts decimal numbers into ternary (base 3) and hexadecimal (base 16) using a recursive method. The second section uses recursive functions to calculate the first twelve Fibonacci sequence numbers. Additionally, the last section displays the runtime for Fibonacci sequence function computations for values of n from 30 to 35. 

For numbers smaller than its base, the function can immediately return a string representation. For instance, if the number is 0, 1, or 2 in base 3, then it returns ‘0’ , ‘1’, or ‘2’. However, for numbers larger than its base, the function works recursively. It divides the numbers by the base to get the next higher digit, and calculates the remainder to get the current digit. For instance, if the remainder is between 10-15, it converts these values to their corresponding letters a-f. Additionally, by analyzing the runtime data for Fibonacci with various n values, the big O mutation is assumed to be O(2^n). It is shown that as n increases, the runtime rate roughly gets doubled each time, showing the exponential growth pattern. 

This project taught me how implementing recursion can simplify the process of converting numbers to different bases. Additionally, I gained experience working with different bases like ternary and hexadecimal, which helped me deepen my understanding of number systems. Furthermore, I learned that the Fibonacci sequence has an exponential time complexity based on the displayed runtime data. By analyzing the performance of different algorithms, I also recognized the importance of optimization. Optimizing can improve the efficiency of the program, making it better suited for larger inputs. 

Here is the fib3 function that calculates the nth term in a sequence where each term is the sum of the three preceding terms. 


public static int fib3(int n) {
	
  if (n < 3) {
		  
   return 1;
   
		} else {
  
			return fib3(n - 1) + fib3(n - 2) + fib3(n - 3);
   
		}
  
	}


 

![image](https://github.com/user-attachments/assets/3634f00e-0842-4e2e-8c26-3ffaf4ed6d4d)



You can learn more here at the [Recursive_Methods](https://github.com/ellieishii/Recursive_Methods).
