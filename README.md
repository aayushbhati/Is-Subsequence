# Is Subsequence

## Problem Description

Given two strings `s` and `t`, return `true` if `s` is a **subsequence** of `t`, or `false` otherwise.

A **subsequence** of a string is a new string that is formed from the original string by **deleting some (can be none) of the characters** without disturbing the **relative positions** of the remaining characters.  
For example: `"ace"` is a subsequence of `"abcde"` while `"aec"` is not.

## Examples

### Example 1:
**Input:**  
`s = "abc"`  
`t = "ahbgdc"`  
**Output:**  
`true`  

---

### Example 2:
**Input:**  
`s = "axc"`  
`t = "ahbgdc"`  
**Output:**  
`false`  

---

## Constraints
- `0 <= s.length <= 100`
- `0 <= t.length <= 10⁴`
- `s` and `t` consist only of **lowercase English letters**.
