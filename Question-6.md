# Question-6

City coup
Max. Marks: 100
Alice and Angela are playing the City of Wards!

In City of Wards, you can represent the land as a  plane. There are  points on this land, where cities can be built. City of Wards hates floating point, and hence defines the distance between two points as Manhattan Distance, i.e. distance between two points and  is:


Now, Angela wants to build cities on each of these   points. Alice warns her that she should build cities in such a way that the vulnerability of kingdoms is minimized. The vulnerability of a city  is defined as . The vulnerability of the kingdom is the sum of the vulnerability of all the  cities.

More formally, the vulnerability of a city is the product of  (cities vulnerability factor) and the sum of its distance from all other cities. The vulnerability of the kingdom is the sum of the vulnerability of each individual city.

Your task is to help Angela determine the minimum possible vulnerability of her kingdom if she places cities optimally.

Input format

The first line contains  denoting number of test cases per file.
The next line contains  denoting the number of points.
The next  points contain  integers each  denoting the  and  coordinate of the city.
The next line contains  space-separated integers denoting the array .
Output format
For each test case, print the minimum vulnerability.
Constraints



Sum of  over all the  lines in a single file is 

SAMPLE INPUT 
1
2
0 0
0 1
10 2000
SAMPLE OUTPUT 
2010
Explanation
The distance of  from  is . Since there are only  cities, the choice of where to build a city doesnt matter and we always have a vulnerability of .