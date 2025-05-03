# Programming Data Structures and Algorithms
---
## Some algorithms must know and asked by many companies

### 1. Two Pointers
In this coding pattern, pointers are references to an array/list
indexes. By using two pointers, we can process two
elements at a time in a single loop. The two pointers iterate
over an array/list in certain directions until some conditions
are fulfilled and process two index elements simultaneously.
The pattern is often used when -
   - array/list is sorted and a comparison needs to be done
between its elements.
   - array/list elements need certain rearrangements/removal
in-place.

*The two pointers are typically represented by i and j.*

#### Sample Questions - 
- Two Sum II - Input Array Is Sorted
- Container With Most Water
- Remove Duplicates from Sorted Array
- Next Permutation
- Trapping Rain Water
---

### 2. Fast and Slow Pointers

In this coding pattern, two pointers are used by name fast
and slow. These pointers iterate an array/list at different
speeds. The algorithm involved is termed as, Hare and
Tortoise algorithm.

#### Sample Questions- 
- Linked List Cycle
- Middle of the Linked List
- Palindrome Linked List
- Happy Number
- Circular Array Loop
---

### 3. Sliding Window
The sliding window pattern is a common algorithmic
technique used in solving problems that involve arrays,
strings, or other sequence-like data structures. It involves
defining a window or a subarray/substring within the given
data and then iteratively moving or sliding the window to
solve the problem efficiently.

Here's how the sliding window pattern typically works:
Initialize two pointers, "start" and "end", which define the
current window.

1. Slide the window by moving the "end" pointer to the
right, expanding the window.
2. Check if the current window satisfies the problem's
constraints or requirements.
3. If the window satisfies the constraints, update the result
or take any required action.
4. Shrink the window by moving the "start" pointer to the
right, removing elements from the window.
5. Repeat steps 2 to 5 until we have processed all elements
in the given data structure.

#### Sample Questions - 
- Longest Substring Without Repeating Characters
- Longest Repeating Character Replacement
- Sliding Window Maximum
- Permutation in String
- Fruit Into Baskets
---
