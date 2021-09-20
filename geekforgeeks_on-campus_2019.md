# On-Campus 2019 (Last Updated: 07 Jan, 2020)

## Round 2 - Coding round
1. A company has one stage, many events are scheduled at different time slots. Only one event can be scheduled at a time. We have to find the maximum number of events that can be scheduled. Input: startTime[ ], endTime[ ].
2. Given a string, we have to replace the minimum number of characters such that all adjacent characters are different. We have to return the minimum number of replacements needed.
4 MCQs based on probability, general maths, and DP.

## Round 3 - Skype Interview ( 1.5 hr)

1. In a directed graph, you need to tell the node from which all other nodes can be visited. Code the brute force solution and dry run it for the given test cases.
2. Optimise the previous solution.
3. Detect loop in a linked list.
4. Prove the correctness of the previous solution.
5. Write a code to distribute c chocolates among n students such that the sum of the absolute difference of the chocolate received by the adjacent students ( abs( (ai)-(ai+1) ) ) is minimum. ( O(1) time ). Eg. 2 3 4 1 3 chocolates distributed to 5 students than sum is 7.
6. In the previous solution ( after chocolate distribution ) rearrange the students in such a way that the sum of the absolute difference between the adjacent student is maximum.

## Round 4 - Skype Interview ( 1 hr)

1. Write dfs iterative code for a graph.
2. Given a linked list print the last nth node.
3. Given disks and rings. You have an array representing the size of those disks. And another array having sizes of the rings.
- Rules:
  - A smaller disk can pass bigger ring.
  - A disk equal to another disk will be stuck at the top of the disk.
  - If there’s a disk stuck at the top of a ring, no other disk can pass through it, it will be stuck at its top.
  - Only one more disk can be stuck at the top of the first ring.
  - If one disk is at the top, no more insertion of a disk can be done.
- Write a code to find the number of disks that can be inserted. Start inserting from the first element of the array. Only one disk can be inserted above the first ring.

```txt
Input :
4 5 6 2 1-> rings
1 1 2 3 4->disks
Explanation :4D 4R 3R 3D 2D 2R 1D 1D 1R
Output :Ans: 5

Input :
4 5 1 2 1-> rings
1 1 4 3 4->disks
Explanation :4D 4R 5R 1D 1D 1R 2R 1R 
Output :Ans: 3
```
4. Optimise the previous solution.
