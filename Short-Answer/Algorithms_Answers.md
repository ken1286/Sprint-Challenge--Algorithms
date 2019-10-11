#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n)
The number of operations for this algorithm scale linearly with n.

b) O(n^2)
The number of operations for this algorithm increase proportionaly with n^2

c) O(n)

## Exercise II

1. Drop an egg from the middle floor, n/2
2. Drop from this middle floor. If the egg breaks, find the midpoint between the ground floor and the current floor-1 and repeat this step. If it doesn't break, find the midpoint between the top floor (n) and your current floor+1. Repeat steps 1 and 2 with the new midpoints until the egg's breakpoint is found.

Runtime complexity is O(log(n))
