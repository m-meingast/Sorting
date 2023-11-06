# Sorting

Your task is to implement a sorting algorithm of your choice

Test your implementations with different sizes of arrays.
It is sufficient if you use int arrays.

## Generate Random Numbers

Write a method to generate an array of size N initialised with random numbers. 
For random numbers you can use the following expression:

~~~java
// Values are smaller 100 (= bound).
int number = new Random().nextInt(100);
~~~

## Sort Array

Write a method that implements the sorting algorithm.
In addition, write another method to print the array to the console.

## Measure Runtime

Write a method to do an execution time analysis of your algorithm.
Use the following code snippet to measure the execution time.

~~~java
long startTime = System.nanoTime();
/*
 * Method call of your algorithm
 */
long endTime = System.nanoTime();
System.out.println("time: " + (endTime - startTime));
~~~

For which array size does the execution time start to rise significantly?

## Compare Algorithms

Compare the execution time of your algorithm with the execution time of your QuickSort or BubbleSort implementation.
Which one is faster?

**Use methods for the individual tasks**. You can also use as many helper methods, as you need. Mark them as private.