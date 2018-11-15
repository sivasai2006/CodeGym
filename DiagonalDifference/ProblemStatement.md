Given a square matrix, calculate the absolute difference between the sums of its diagonals.
For example, the square matrix  is shown below:<br />
` 1 2 3 ` <br />
` 4 5 6 ` <br />
` 9 8 9 ` <br />
The left-to-right diagonal => 1 + 5 + 9 = 15. The right to left diagonal = 3 + 5 + 9 = 17. Their absolute difference is |15 - 17| = 2.
# Function description #
Complete the diagonalDifference function in the editor below. It must return an integer representing the absolute diagonal difference.
diagonalDifference takes the following parameter:
•	arr: an array of integers .
# Input Format #
The first line contains a single integer, n, the number of rows and columns in the matrix . 
Each of the next n lines describes a row, arr[i], and consists of  space-separated integers arr[i][j].
# Constraints #
•	-100<=arr[i][j]<=100
# Output Format #
Print the absolute difference between the sums of the matrix's two diagonals as a single integer.
# Sample Input #
`3`<br />
`11 2 4`<br />
`4 5 6`<br />
`10 8 -12`<br />
# Sample Output #
`15`
# Explanation #
The primary diagonal is:
`11`<br />
`   5`<br />
`     -12`<br />
Sum across the primary diagonal: 11 + 5 - 12 = 4
The secondary diagonal is:
`     4`<br />
`   5`<br />
`10`<br />
Sum across the secondary diagonal: 4 + 5 + 10 = 19 
Difference: |4 - 19| = 15
Note: |x| is the absolute value of x
