#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n): As the size of the input (n) increases, the time will increase linearly.

b) O(n^2): For loop + nested while loop = n \* n - The time would increase at a faster rate quadratically.

c) O(n): With no loop, the n is still being called recursively 'n times' - which will make the time increase linearly.

## Exercise II

- O(log n)
  - Find the midpoint of n-stories,
    - (n // 2) - floor division
  - Drop the egg at the midpoint,
    - If the egg breaks, eliminate the stories (floors) above
    - If the egg doesn't break, eliminate the stories (floors) below
      - `non_el` = stories that weren't eliminated
  - Repeat steps with the midpoint of `non_el`
