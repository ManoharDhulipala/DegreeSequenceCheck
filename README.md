# DegreeSequenceCheck
A degree sequence is a set of values that represents the number of nodes by the number of values in the set and the value of each number represents the degree for each node.

My algorithm to determine whether or not a graph can be formed is determined by the following steps.

1. Sum up the sequence and if it is odd, the sequence is unable to form a graph or in other words, not graphic.
2. If the sequence is all 1's & 0's, the sequence is able to form a graph or in other words, graphic.
3. Order the sequence, and observe the first number in the sequence, which we will call x. Look at the next x values in the array.
  a. If any of the next x values are 0, the sequence is not graphic.
  b. Else, subtract the next x values by 1.
4. Repeat back to step 2.
