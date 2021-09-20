# SDE3(On Campus) (Last Updated: 28 Oct, 2018)

## Online Coding Round 2

### Question 1
**N** nodes where given. Any two nodes where connected with each other if the **GCD (node1, node2)** was greater than a given threshold value**(T)**. The problem was to find if two nodes given were having any path between them for Q queries.Applying modified BFS after creating the adjacency matrix passed most test cases.

### Question 2

Modified Coin Change Problem.
There were **N** coins which had to be converted into **M** coins. If you were at **X** coins, then you could go to **(X + Y)** by adding **Y** coins where **Y** is a **prime factor** of **X**. Adding a Y constituted a **single step**. The problem was to find the minimum number of steps required for the conversion.The problem could be solved by **Dynamic Programming**.

---

## Interview Round 1

### Problem 1
Find the maximum path sum in a binary tree. The path could start and end at any node in the tree. I discussed with him my approach and he was quiet interested in it. He told me to write a pseudocode for it. Later he found some mistake and told me to re-check. After sometime I gave him a O(n) approach. He was satisfied with it.

### Problem 2
Find LCA in a Binary Tree. I was stuck in finding LCA in a BST instead of a binary tree. So first I gave him a O(height) solution of finding LCA in BST. But he was expecting a O(n) solution for binary tree. So I gave him another solution to find LCA using path traversal in O(n).

### Problem 3
There are N commits to a repository. For a particular commit x, it is known that there was no error in the repo and after a commit Y there is some mistake in the repository. The problem was to find the commit that caused the error.
I wrote the Binary Search Algorithm for the problem with complexity O(log(n)). After dry Run, he was convinced that the solution will work for the problem.

---

## Interview Round 2

### Problem 1
I was given a Queue data structure that supports standard operations like enqueue() and dequeue().I had to implement a Stack data structure using only instances of Queue and queue operations allowed on the instances.
Solution : https://www.geeksforgeeks.org/implement-stack-using-queue/

### Problem 2
Implement LRU cache. I was implementing it using hashed map and linked list O(n). He was expecting O(1) for page replacement. Then I used Queue using doubly linked list in my approach.
Solution: https://www.geeksforgeeks.org/lru-cache-implementation/

---

## Reference
- https://www.geeksforgeeks.org/traveloka-interview-experience-for-sde3on-campus/
