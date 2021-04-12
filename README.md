# DSA-Sorting
Sorting Algorithms Drills and Practice

## Understanding merge sort

Given the following list of numbers 21, 1, 26, 45, 29, 28, 2, 9, 16, 49, 39, 27, 43, 34, 46, 40

* What is the resulting list that will be sorted after 3 recursive calls to mergesort?
  ```
  21, 1, 26, 45, 29, 28, 2, 9, 16, 49, 39, 27, 43, 34, 46, 40

  right1: 21, 1, 26, 45, 29, 28, 2, 9
  left1: 16, 49, 39, 27, 43, 34, 46, 40

  right11: 21, 1, 26, 45
  left11: 29, 28, 2, 9

  right12: 16, 49, 39, 27
  left12: 43, 34, 46, 40

  ```
* What is the resulting list that will be sorted after 16 recursive calls to mergesort?
* What are the first 2 lists to be merged?
* Which two lists would be merged on the 7th merge?

## Understanding quicksort
1) Suppose you are debugging a quicksort implementation that is supposed to sort an array in ascending order. After the first partition step has been completed, the contents of the array is in the following order: 3 9 1 14 17 24 22 20. Which of the following statements is correct about the partition step? Explain your answer.

The pivot could have been 17, but could not have been 14
The pivot could have been either 14 or 17
Neither 14 nor 17 could have been the pivot
The pivot could have been 14, but could not have been 17
2) Given the following list of numbers 14, 17, 13, 15, 19, 10, 3, 16, 9, 12 show the resulting list after the second partitioning according to the quicksort algorithm.

When using the last item on the list as a pivot
When using the first item on the list as a pivot