# [fit] Permutations

---

##The distinct ways that a group of items can be arranged.

---

#Example: ```[1,2,3]```
```javascript
[
  [ 1, 2, 3 ],
  [ 1, 3, 2 ],
  [ 2, 1, 3 ],
  [ 2, 3, 1 ],
  [ 3, 1, 2 ],
  [ 3, 2, 1 ]
]
  ```

---

# How many permutations?

^It turns out that we can mathematically determine the number of permutations for a given set of values. If we can only use each value one time (but must use it 1 time), then the solution is n!.

---

# What kind of problems will you see?

---

## Given two strings, determine if they are permutations of one another.

---

## Is "stop" an anagram of "tops"?

^ Yes, this is the same as the previous question. It's just asked in a different way.

---

## How many ways can we...?

^Example- There are 4 restaurants that I want to visit that are across the city from one another. How many different ways (order) can I visit the restaurants?
A shelter has 4 dogs. How many different ways can the dogs be adopted among 4 people who are interested in adopting?

---

## Write an algorithm to determine all possible permutations of a given string.

---

# Traveling Salesman Problem
> The Traveling Salesman Problem (often called TSP) is a classic algorithmic problem in the field of computer science. It is focused on optimization. In this context better solution often means a solution that is cheaper. TSP is a mathematical problem.
--Wikipedia

^ This is a big problem, but when broken down into parts, one of the parts is essentially a permutation problem.

---

#[fit] Permutation Algorithms to Consider
- [Backtracking](https://www.youtube.com/watch?v=AfxHGNRtFac)
- [Heap's Algorithm](https://en.wikipedia.org/wiki/Heap%27s_algorithm)
- [Lexicographic(Sorted) Ordering](https://www.quora.com/How-would-you-explain-an-algorithm-that-generates-permutations-using-lexicographic-ordering)
