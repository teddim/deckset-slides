# Searching An Array

---

#Objectives

- Demonstrate the linear search algorithm
- Demonstrate the binary search algorithm

---

# Natural ways of Searching

^ I need 2 volunteers
2 decks of cards, sorted and unsorted

---

# Rules
- Your deck will either be unsorted or sorted
- You can only look at one card at a time
- You have to go slow enough for us to see what you are doing
- Approximations are ok

^ first person gets unsorted cards (why did you make that search choice?)
another person gets unsorted cards (same question)
Give card I'm looking for
Second time around - whiteboard which search algorithm you would use. Sorted deck, unsorted deck
What is the worst case Big O?

---

# Linear Search
## Brute Force
## `O(n)`

^ looking at each item in the array. Worst case is having to look at all of them to find the one you want...or to discover that it isn't there.

---

# Binary Search
## `O(log n)`

^ cutting the number you need to look at in half each time.
Array must be sorted or the strategy doesn't work
If the value of the middle element is bigger than what you are looking for than look from that value to the end. If it is smaller than look from the beginning up through that value.
Let's try the game again with these new search algorithms

---
## You try it
###`Exercises$: mocha test/array-search`

^ Run the tests to see what you need to get to pass. Do both linear and binary search. We will share solutions in 15 minutes.
