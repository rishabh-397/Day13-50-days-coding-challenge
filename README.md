# Day13-50-days-coding-challenge
# 🚀 Day 13 – 50 Days of Coding Challenge

Welcome to Day 13 of my **#50DaysOfCodingChallenge**!  
Today I solved two problems based on **sign determination** and **linked list deduplication**.

---

## ✅ Problem 1: Sign of the Product of an Array

### 🔍 Problem Statement

Given an integer array `nums`, determine the sign of the product of all its elements using a function `signFunc(x)`:
- Returns `1` if `x > 0`
- Returns `-1` if `x < 0`
- Returns `0` if `x == 0`

🔗 Instead of calculating the entire product (which may overflow), we:
- Return `0` if any element is zero
- Count negatives and return `-1` if odd, else `1`

---

### ✍️ Example

```txt
Input: [-1, -2, -3, -4, 3, 2, 1]
Output: 1
⏱ Time & Space Complexity
Time: O(n)

Space: O(1)

✅ Problem 2: Remove Duplicates from Sorted Linked List
🔍 Problem Statement
Given a sorted linked list, delete all nodes that have duplicate numbers, leaving only distinct numbers.
Input:  [1,2,3,3,4,4,5]
Output: [1,2,5]
🔧 Key Concepts
Use of dummy node to handle edge cases

Efficient traversal with prev and current pointers

📚 Concepts Covered
Mathematical sign evaluation

Product optimization without overflow

Linked list pointer manipulation

Deduplication of sorted lists
