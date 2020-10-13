#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) This snippet is `linear time O(n)`. With each iteration of the while loop, it's increasing the size of `a` until `a > n * n * n`.

b) This snippet is `linearithmic time or O(n log n)` because the `while` loop inside of the `for` loop doubles `j` with each execution, making it run slower.

c) This snippet is also `linear time or O(n)` because the function recursively calls itself `n` amount of times.

## Exercise II

In this case scenario, floor `f` would be considered the target floor. Since we're speaking of a building here, the floors go in ascending order. In that case, we can use a `binary search` to determine where floor `f` is exactly, minimizing the number of dropped and broken eggs.

The runtime complexity of my solution would be `logarithmic time` or `O(log n)`, since we're not dropping an egg on every floor (which would be `linear time` or `O(n)`)
