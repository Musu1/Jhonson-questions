# Question-1

Digit products
Max. Marks: 100
For any number , the prime factorization is defined as . Then, its weight  is calculated as:  .  

You are given a number . Determine the summation of weights of the product of digits of all the numbers from  to .

Input format

The first line of the input contains an integer  denoting the number of test cases.
Each of the next  lines contain an integer .
Output format

Print the answer for each test case in a separate line.

Constraints



SAMPLE INPUT 
2
4
20
SAMPLE OUTPUT 
5
48
Explanation
Sample Case 1: For N as 4, Product of digits of 1, 2, 3 and 4 are again 1, 2, 3 and 4 itself respectively.

1 has no prime factors, it's weight will be 0
2 can be expressed as 2^1, it's weight is given by 2*(1 % 2) = 2
3 can be expressed as 3^1, it's weight is given by 3*(1 % 2) = 3
4 can be expressed as 2^2, it's weight is given by 2*(2 % 2) = 0

Sum of all the weights = 0 + 2 + 3 + 0 = 5. Hence, the answer is 5.