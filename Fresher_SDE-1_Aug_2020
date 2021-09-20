# Fresher SDE-1, Aug 2020

## Round 01

Online Test comprised of 3 algorithmic Questions. Duration of round was 90 minutes.

### Ways to make coin change

You are given an infinite supply of coins of each of denominations D = {D0, D1, D2, D3, ...... Dn-1}. You need to figure out the total number of ways W, in which you can make a change for value V using coins of denominations from D. Print 0, if a change isn't possible.

#### Input Format
```txt
The first line of input contains an integer N, representing the total number of denominations.
The second line of input contains N integers values separated by a single space. Each integer value represents the denomination value.
The third line of input contains the value of V, representing the value for which the change needs to be generated.
```

####Output Format:
```txt
For each test case, print an integer denoting the total number of ways W, in which a change for V is possible.
```

#### Note:
```txt
You do not need to print anything, it has already been taken care of. Just implement the given function.
```

#### Constraints :
```txt
1 <= N <= 10
1 <= D[i] <=10^5
1 <= V <= 2 * 10^3

Where 'D[i]' represent the value of ith denomination. 

Time Limit: 1sec
```

#### Tried Approach

I first tried to solve the problem using BackTracking and was able to pass only 8 test cases out of 13. Then I checked the constraints again and realised that for clearing all 13 test cases I have to submit a solution with worst time complexity O(n^2). I tried to solve the question again but due to limited time couldn't solved it completely.

### Longest increasing subsequence

For a given array with N elements, you need to find the length of the longest subsequence from the array such that all the elements of the subsequence are sorted in strictly increasing order.
Strictly Increasing Sequence is when each term in the sequence is larger than the preceding term.

#### For Example:
```txt
[1, 2, 3, 4] is a strictly increasing array, while [2, 1, 4, 3] is not.
```

#### Input Format:
```txt
The first line of input contains an integer 'N', representing the size of the array.
The second line of input contains 'N' space-separated integers, representing the elements of the array.
```

#### Output Format:
```txt
The only output line contains one integer representing the length of the longest increasing subsequence.
```

#### Note:
```txt
You do not need to print anything; it has already been taken care of. Just implement the given functions.
```

#### Input Constraints
```txt
1 <= N <= 10^5
-10^5 <= element <= 10^5

Time Limit: 1sec
```

#### Tried Approach

I read the question first and the constraints. After reading the question I wrote the recurrence relation on paper and verified with the help of some examples. After verifying the recurrence relation, I coded the memoized solution and was able to pass all test cases.

---

## Round 02

It was a 60 minute virtual face 2 face round with 2 senior software engineers of the company. Interview started with brief introduction by the engineers followed by my Introduction. Interview started at 3:00 P.M and lasted till 4:10 P.M. Google Doc was used for coding purposes.

### Search an element in a sorted and rotated array

Aahad and Harshit always have fun by solving problems. Harshit took a sorted array and rotated it clockwise by an unknown amount. For example, he took a sorted array = [1, 2, 3, 4, 5] and if he rotates it by 2, then the array becomes: [4, 5, 1, 2, 3].
After rotating a sorted array, Aahad needs to answer Q queries asked by Harshit, each of them is described by one integer Q[i] which Harshit wanted him to search in the array. For each query, if he founds it, he had to shout the index of the number, otherwise, he had to shout -1.

#### Input Format:
```txt
The first line of input contains the size of the array: N
The second line contains N single space-separated integers: A[i].
The third line of input contains the number of queries: Q
The next Q lines of input contain: the number which Harshit wants Aahad to search: Q[i]
```

#### Output Format:
```txt
For each test case, print the index of the number if found, otherwise -1.
Output for every test case will be printed in a separate line.
```

#### Note:
```txt
You are not required to explicitly print the expected output, just return it and printing has already been taken care of.
```

#### Constraints:
1 <= N <= 10^6
-10^9 <= A[i] <= 10^9
1 <= Q <= 500
-10^9 <= Q[i] <= 10^9

Time Limit: 1sec
```

#### Tried Approach

1. I first solved the problem with brute force i.e using linear search. Complexity of solution was O(N) . Interviewers asked me to optimise more.
2. Then I used the fact that initially array was sorted , so I started thinking in the direction of binary search and was able to propose a solution with O(NLogn) Complexity.
3. Then Interviewers asked me about the explanation of the solution and I was able to tell them correctly. Interviewers were satisfied with my solution

### Construct Binary Tree from given Parent Array representation

Given an array parent which represents a binary tree such that parent-child relationship is defined by ('PARENT'[i], 'i') which means that parent of i is 'PARENT'[i]. The value of the root node will be i if -1 is present at 'PARENT'[i].

---

## Round 03

It was a face 2 face algorithmic round taken by Senior Backend engineer. Interview Round Started at around 2:00 P.M and lasted till 3:05 P.M. Interview started with the brief introduction followed by 2 algorithmic questions. Interviewer was focusing problem solving skills. After discussing the approach, Coding part was to be done on google doc.

### Maximum path sum in the matrix

You have been given an N*M matrix filled with integer numbers, find the maximum sum that can be obtained from a path starting from any cell in the first row to any cell in the last row.
From a cell in a row, you can move to another cell directly below that row, or diagonally below left or right. So from a particular cell (row, col), we can move in three directions i.e.
```txt
Down: (row+1,col)
Down left diagonal: (row+1,col-1)
Down right diagonal: (row+1, col+1)
```

#### Input Format :
```txt
The first line contains an integer 'T', which denotes the number of test cases or queries to be run. Then the test cases follow.
The first line of each test case contains two Integers 'N' and 'M' where 'N' denotes the number of rows in the given matrix. And 'M' denotes the number of columns in the given matrix.
The next 'N' line of each test case contains 'M' space-separated integers denoting the cell elements.
```

#### Output Format :
```txt
For each test case/query, print the maximum sum that can be obtained by taking a path as described above.
Output for every test case will be printed in a separate line.
```

#### Note :
```txt
You do not need to print anything. It has already been taken care of.
```

#### Constraints :
```txt
1 <= T <= 50
1 <= N <= 100
1 <= M <= 100
-10^4 <= matrix[i][j] <= 10^4

Where 'T' is the number of test cases.
Where 'N' is the number of rows in the given matrix, and 'M' is the number of columns in the given matrix.
And, matrix[i][j] denotes the value at (i,j) cell in the matrix.

Time Limit: 1sec
```

### Partition equal subset sum

You are given an array 'ARR' of 'N' positive integers. Your task is to find if we can partition the given array into two subsets such that the sum of elements in both subsets is equal.
For example, let’s say the given array is [2, 3, 3, 3, 4, 5], then the array can be partitioned as [2,3,5], and [3,3,4] with equal sum 10.

#### Follow Up:
```txt
Can you solve this using not more than O(S) extra space, where S is the sum of all elements of the given array?
```

#### Input Format:
```txt
The first line of input contains an integer 'T' representing the number of test cases or queries to be processed.
Then the test case follows.
The first line of each test case contains an integer 'N', denoting the size of the array.
The second line of each test case contains 'N' single space-separated integers representing the array elements.


#### Output Format:
```txt
For each test case, print “TRUE” or “FALSE” denoting whether we can partition into two equal subset-sum or not, in a separate line. 
```

#### Note:
```txt
You do not need to print anything; it has already been taken care of. Just implement the given function.
```

#### Constraints:
```txt
1 <= 'T' <= 10
1 <= 'N' <= 100 
1 <= 'ARR'[i] <= 100

Time Limit: 1 sec
```

## Reference
- https://www.codingninjas.com/codestudio/interview-experiences/interview-experience-by-hritik-off-campus-aug-2020-138
