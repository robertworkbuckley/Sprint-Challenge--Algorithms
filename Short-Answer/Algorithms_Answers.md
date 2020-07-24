#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
    - Function runs up to n cubed (a < n * n * n), but with each loop through a increases by n squared. So it will only take "n" number of loops to complete.

b) O(log n)
    - It starts a loop that will run "n" times, but then each loop through it halfs the amount of loops its required to go through. 

c) O(n)
    - This recursive function is continue to call itself through the range of "n". The relationship between the increase in "n" and the increase in calculations required, is linear.

## Exercise II
    -start by dropping one egg from the middle floor len(n) //2
    -if egg breaks go down the half the floors, relative to current position.
    -if egg doesn't break go up half the floors, relative to current position.
    -continue a recursive loop until egg doesn't break and the the remaining floors, relative to current recursion, to go up is only one. Then return this floor.
    This should produce O(log n). Each loop through it is eliminating half of the options. 

