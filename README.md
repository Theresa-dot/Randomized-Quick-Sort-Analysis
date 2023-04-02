# Randomized-Quick-Sort-Analysis
Plotting randomized, rightmost, and midpoint quicksort to explain the efficiency of randomized quicksort by taking input size as x axis and time as y axis

Randomized quicksort will take a random element as pivot, midpoint quicksort takes midpoint as midpoint and rightmost quicksort take rightmost element as pivot.

The plot shows the time taken by each of the three algorithms to sort randomly generated arrays of different sizes ranging from 10K to 100K with a step size of 10K. As the input size increases, the time taken to sort the array also increases.

We can see that the rightmost_quicksort algorithm takes the longest time to sort the arrays, whereas the midpoint_quicksort algorithm takes the least amount of time. This is because selecting the rightmost element as the pivot can lead to worst-case time complexity in some cases, whereas selecting the middle element as the pivot generally results in more balanced partitions and faster sorting.

The random_quicksort algorithm falls somewhere in between the other two algorithms in terms of time taken, as the random selection of pivot elements can sometimes result in more balanced partitions and faster sorting, but it can also result in unbalanced partitions and slower sorting in some cases. Overall, the plot shows that the choice of pivot element can have a significant impact on the efficiency of the quicksort algorithm.
