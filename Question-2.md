# Question-1

Misha and numbers
Max. Marks: 100
Misha is preparing for an interview and she came across the following problem:

She is given three numbers , , and . She is required to check if the digits of  and   can be permuted to get   and  such that the following equation holds true:


Print YES if the above equation holds true, otherwise NO.

Input format

The first line of the input contains an integer  denoting the number of test cases.
Each of the next  lines contains four single-spaced integers denoting    and   as described in the problem statement.
Output format

For each of the  lines, print YES or NO in a single line.

Constraints

 contain at most  digits ranging from  to .
 can contain leading zeros.
SAMPLE INPUT 
2
2 01 11 21
2 11 12 21
SAMPLE OUTPUT 
YES
NO
Explanation
Sample Case 1:

01 can be permuted to form 10
11 can be left as it is.
11 + 10 = 21
Hence, the answer is YES.

Sample Case 2:

No permutation of 11 and 12 can give the sum as 21.
Hence, the answer is NO.