# Question-5

Let's play Tetris!
Max. Marks: 100
Alice is working on a project to develop the most world-renowned Tetris game.

She assumes a simplified version of the game. The only shape falling from the sky is a square. A square can fall on the ground or gets connected to another square. A square is connected to another square if the falling square touches the top of the other square. 

The screen is  units long. There are following  events that can occur during the duration of the game:

1. : For some purposes of computation, Alice needs the maximum height attained by any square in the range .

2. : A square whose length of the side is  starts falling from the sky, with its bottom-left corner at tthe position . The square falls vertically until it hits the ground or gets connected to another square. Recall that even if it touches the top of some square, it will get connected and stop falling. You may refer to the sample explanation for clarity.

Initially, there are no squares. Hence you may assume ground to be at the height . 

Input format

The first line contains  denoting the number of test cases per file.
The first line of each test case contains  integers  and  denoting the length of the screen and number of queries respectively.
The next  lines contain queries as described in the problem statement.
Output format

For each query of type , print the maximum height attained by any square in the range .

Constraints






 
Sum of  and  over all the test cases in a file is  respectively.

SAMPLE INPUT 
1
10 4
1 4 3
0 1 5
1 2 2
0 1 5
SAMPLE OUTPUT 
3
5
Explanation
The first query says that a square of side length  falls vertically with its bottom left corner at position . Hence, it will increase the height of positions from .

In the second query, we asked the maximum height in the range  which turns out to be 3 due to the square just added.

In the third query, the next square spans from  and hence it touches the initial square. It does not fall down when it's connected. Hence, the answer for the  query is now 