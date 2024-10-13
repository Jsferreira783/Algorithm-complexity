==========================Problem 1: Mathematical Foundations====================================================
Explanation: 

The program calculates the total distance between a series of delivery points and finds the sum of the first NNN natural numbers.First,
the user is asked to input how many delivery points there are. Then, for each delivery point, the user enters the x and y coordinates. 
These coordinates are stored in a list (vector) of pairs.The program then calculates the total distance traveled by summing the distances between each 
consecutive pair of delivery points using the Pythagorean theorem (to find the distance between two points). It also calculates the sum of the first NNN natural 
numbers using the formula N(N+1)2\frac{N(N + 1)}{2}2N(N+1) . 

Finally, it prints out both the total distance and the sum of the first NNN natural numbers, formatted in a way that lists the delivery points and results clearly.
The code runs in sequence: taking input, processing the distance and sum, and then displaying the output. 


============================Problem 2 Algorithm Complexity============================================================
Explanation: 

This program sorts a list of delivery times using two different sorting methods: Bubble Sort and Merge Sort, and then compares their performance. 
 1. First, the user enters the number of delivery times and the times themselves. 
2. The program sorts the list using Bubble Sort, which compares and swaps each pair of numbers repeatedly until the list is sorted. 
3. Then, it sorts the list again using Merge Sort, which divides the list into smaller parts, sorts them, and then merges the parts back together in order. 
4. After sorting with both methods, the program displays the sorted list, shows how much time each method took, and explains the time complexity of each method (Bubble Sort: \(O(N^2)\), Merge Sort: \(O(N \log N)\)). 
The code compares these two algorithms to show that Merge Sort is faster and more efficient than Bubble Sort, especially with large lists. 


===========================Problem 3 Recursive Algorithms=============================================================
Explanation: 

The enhanced program for the Tower of Hanoi problem is designed to clearly demonstrate the process of moving a specified number of discs from one rod to another while following the game rules. By displaying each move with corresponding step numbers and providing clear instructions and summaries, users can easily understand how the recursive algorithm works and how the discs are transferred. The program’s total move count gives an indication of the efficiency of the recursive solution, which is O(2N)O(2^N)O(2N) in terms of time complexity. 
 
