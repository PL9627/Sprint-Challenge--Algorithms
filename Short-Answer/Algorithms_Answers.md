#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)  O(n)


b)  O(n^c)


c)  O(n)

## Exercise II
    With a building with n floors, the worst case scenario would be to throw an egg from the first floor to see if it breaks and repeat the process on each floor until the egg breaks.  This would be too long of a process and the runtime would be too long to be a viable solution.
    
    It would be best to divde and conquer the building. If we are able to determine the midpoint of the building, we would throw an egg and see if it breaks. If it doesn't; we move up to the midpoint floor between the previous midpoint floor and the top floor. Repeat the process until the egg breaks.

    If the egg breaks, then we would move down from the original midpoint floor or revised midpoint floor to the new midpoint floor and throwing an egg. Repeat the process until the egg does not break. In this way, do we find floor f and the process would be much more efficient. 

    This requires a merge sort method to solve the problem. The merge sort method has a runtime complexity of O(n * log(n)).

