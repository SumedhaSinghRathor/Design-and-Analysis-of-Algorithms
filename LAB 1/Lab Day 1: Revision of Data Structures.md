## Lab Day 1: Revision of Data Structures

<ol>
  <li>Does this work?</li>
  <li>If yes, than this is the second bullet point.</li>
</ol>

**1.1 Aim of the program:** Write a program to find out the second smallest and the second largest element stored in an array of n integers.  
&nbsp; _Input:_ Size of an array is 'n' and read 'n' number of elements from a disc file.  
&nbsp; _Output:_ Second smallest, second largest.  
  
**1.2 Aim of the program:** Given an array arr[] of size N, find the prefix sum of the array. A prefix sum array is another array prefixSum[] of the same size, such that the value of prefixSum[i] is arr[0] + arr[1] + arr[2] . . . arr[i].  
&nbsp; _Input:_ 3 4 5 1 2  
&nbsp; _Output:_ 3 7 12 13 15  

**1.3 Aim of the program:** Write a program to read ‘n’ integers from a disc file that must contain some duplicate values and store them into an array. Perform the following operations on the array.  
- Find out the total number of duplicate elements
- Find out the most repeating element in the array  
&nbsp; _Input:_ Enter how many numbers you want to read from file: 15  
&nbsp; _Output:_ The content of the array: 10 40 35 47 68 22 40 10 98 10 50 35 68 40 10  
&nbsp; &nbsp; Total number of duplicate values = 4  
&nbsp; &nbsp; The most repeating element in the array = 10  

**1.4 Aim of the program:** Write a function to ROTATE_RIGHT(p1, p2) right an array for first p2 elements by 1 position using EXCHANGE(p, q) function that swaps/exchanges the numbers p &amp; q. Parameter p1 be the starting address of the array and p2 be the number of elements to be rotated.  
&nbsp; _Input:_ Enter an array A of size N (9): 11 22 33 44 55 66 77 88 99  
&nbsp; &nbsp; &nbsp; Call the function ROTATE_RIGHT(A, 5)  
&nbsp; _Input:_ BEFORE ROTATE: 11 22 33 44 55 66 77 88 99  
&nbsp; &nbsp; &nbsp; AFTER ROTATE: 55 11 22 33 44 66 77 88 99  
