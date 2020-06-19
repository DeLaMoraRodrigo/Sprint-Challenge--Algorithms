#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n) The function does "n" amount of actions so the runtime will increase linearly with n


b)O(n^2) The function does "n" amount of actions twice because there is a loop nested inside of another loop


c)O(n) The function does "n" amount of actions, one for each recursive call until n = 0

## Exercise II
We would do a binary search of the floors. We would be checking the midpoint of the list of floors and checking if 
the egg gets broken. Then if the egg is broken on the midpoint we set the new top floor to be one floor below the
middle. Then we take the midpoint again and check if the egg breaks. If the egg is not broken on the midpoint then
we set the new bottom floor to be one floor above the middle. Then we take the midpoint again and check if the egg
breaks. We conitinue until there are no more floors to check. If the egg breaks on the last check then that floor is 
"f", if the egg doesn't break then the floor above the last floor we checked will be "f". We are halving the number
of floors each time so the complexity is O(log n)

