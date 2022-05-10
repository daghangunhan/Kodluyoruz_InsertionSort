# Exercise for Insertion Sort Algorithm

## Question 1:

Write the stages of the **[22,27,16,2,18,6]** sequence according to the sort type.

Write the Big-O notation.

**Time Complexity:**
- **Average case:** The number we are looking for is in the middle of the array.
- **Worst case:** The number we are looking for is at the end of the array.
- **Best case:** The number we are looking for is at the beginning of the array.

Which case given above does the number 18 fall into after the array is sorted?

## Question 2:

Write the first 4 steps of **[7,3,5,8,2,9,4,15.6]** according to Insertion Sort.

----

## Answer 1:

Stages of the Insertion Sort are given in the Figure below.

![Insertion_1](https://raw.githubusercontent.com/daghangunhan/Kodluyoruz_InsertionSort/main/visuals/Insertion_1.JPG)

Big-O notation for the Insertion Sort Algorithm:

Searching for the smallest number in the rest of the array each time

Number of Operations: n+(n-1)+(n-2)+...+3+2+1=n*(n+1)/2 - **O(n^2)**

- Average case: O(n^2)
- Worst case: O(n^2)
- Best case: O(n)

The number 18 fall into **Average Case** given above after the array is sorted.


## Answer 2:

Stages of the Insertion Sort are given in the Figure below.

![Insertion_2](https://raw.githubusercontent.com/daghangunhan/Kodluyoruz_InsertionSort/main/visuals/Insertion_2.JPG)
