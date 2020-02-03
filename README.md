# Find-All-Occurances-of-A-Number-In-a-Matrix
Given a matrix, this program will find all the occurrences of a number.
Given 𝑀×𝑁 matrix of numbers, find all occurrences of a given number in the matrix using a recursive function. You can search the number in all eight possible directions i.e North, North-East, South etc. Note that there should not be any cycles in the output path. The matrix and the number you have to search for should be taken as user inputs.
```
For an example, consider the below matrix.
[ 3 4 5 6 5 ]
[ 7 2 4 7 4 ]
[ 3 3 1 2 3 ]
[ 4 8 4 3 8 ]
[ 6 5 7 4 9]
If the number you must search is “1234”, the output should be looked like this.
Output :
1 (2,2) 2 (1,1) 3 (0,0 ) 4 (0,1)
1 (2,2) 2 (1,1) 3 (2,0 ) 4 (3,0)
1 (2,2) 2 (1,1) 3 (2,1 ) 4 (1,2)
1 (2,2) 2 (1,1) 3 (2,1 ) 4 (3,0)
1 (2,2) 2 (1,1) 3 (2,1 ) 4 (3,2)
1 (2,2) 2 (2,3) 3 (2,4 ) 4 (1,4)
1 (2,2) 2 (2,3) 3 (3,3 ) 4 (3,2)
1 (2,2) 2(2,3) 3 (3,3 ) 4 (4,3)
```
