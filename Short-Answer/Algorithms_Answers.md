#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) In this snippet the input `n` is being used in a while loop condition and multiplied. This tells me that the greater the condition it will grow exponentialy. I would classify it `O(c^n)` and the runtime will grow at a faster rate.


b) This pseudocode iterates through the size of the input two times. Its always going to loop based on the size of the input `n` in the for loop. In the while loop it will run less times since `j` gets incremented double the amount of j. Time complexity for this snippet falls under `O(n log n)` linearithmic speed where it grows at a sligthly faster rater.


c) In snippet c the input `bunnies` is being recursively iterated through until it equals zero decrementing by 1. The time complexity grows at the same rate as the amount of bunnies grows. This snippet falls under `O(n)` or linear run time.

## Exercise II

First find middle floor in the building
drop egg
as long as eggs keep breaking recurse until you egg doesnt break

if egg is broken
forget the top floors
repeat finding middle floor of the floors below you and dropping egg recursively until you find where it stops breaking `f`

if egg does not break
forget bottom floors
repeat finding middle floor for the floors above you until egg doesnt break

`This algorithm is based on binary search where it attempts by finding the middle first and to cut options in half. The runtime complexity for this is "O(log n)" or logarithmic runtime.`