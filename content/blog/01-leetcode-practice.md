---
title: LeetCode Practice Questions
date: 2025-07-21 14:00:00 +0530
authors: 
  - name: mohdvasm
    link: https://github.com/mohdvasm
tags:
  - python
  - leetcode
prev: /blog
next: /blog
---

This article provides basic and foundational logic thinking to improve problem solving mindset through solving most frequest asked LeetCode interview questions.
<!--more-->

# LeetCode Practice Questions

### 🧮 Math & Number Theory Problems
1. Sum of N Even Natural Numbers  
2. Check for Even Number  
3. Check for Prime Number  
4. Valid Perfect Square  
5. Decimal to Binary  
6. Binary to Decimal  
7. GCD of Two Numbers  

---

### 🔢 List & Sequence Problems
1. Sum of List Elements  
2. Largest Element in a List  
3. Remove Duplicate in a List  
4. Check if All Elements in a List are Unique  
5. Program to Reverse a List  
6. Count Number of Odd and Even Elements in a List  
7. Maximum Difference Between Two Consecutive Elements in a List  
8. Merge Two Sorted Lists  
9. Rotate a List  
10. Merge 2 Lists into Dictionary  
11. Merge Multiple Dictionaries  
12. Words Frequency in a Sentence  
13. Palindromic Tuple  
14. Merge Dictionaries with Common Keys  
15. Check if List is Subset of Another List  

---

### 📄 String Problems
1. Reverse a String  
2. Count Vowels in a String  
3. Check for Same Strings  
4. Check Palindrome  
5. Count Words in a String  
6. Remove Duplicates in a String  
7. Count Consonants in a String  
8. Check for Anagrams  
9. Check Subsequence  
10. Check for Substring  
11. Length of the Longest Word  

---

### 🔷 Pattern Printing Problems
1. Square of Side 'N'  
2. Hollow Square of Side 'N'  
3. Rectangle Pattern  
4. Right Angled Triangle  
5. Inverted Right Angled Triangle  
6. Pyramid Pattern  
7. Inverted Pyramid Pattern  
8. Right Angled Triangle with Numbers  
9. Floyd’s Triangle  
10. Diamond Pattern  
11. Right Angled Triangle II  
12. Sandglass Pattern  
13. Hollow Right Triangle  
14. Hollow Inverted Right Triangle  
15. Number Pyramid Pattern  

---

### 🧰 Miscellaneous Basic Programs
1. Celsius to Fahrenheit  
2. Area of a Rectangle  
3. Distance Covered by a Vehicle  
4. Number of Rounds of Lift  
5. Line Equation


## Pattern Practice Questions

### 1. **Square of side 'N'**

**Input:**  
`N = 4`

**Output:**

```
****
****
****
****
```

**Constraints:** `1 <= N <= 100`

---

### 2. **Hollow Square of side 'N'**

**Input:**  
`N = 5`

**Output:**

```
*****
*   *
*   *
*   *
*****
```

**Constraints:** `2 <= N <= 100`

---

### 3. **Rectangle Pattern**

**Input:**  
`R = 3, C = 6`

**Output:**

```
******
******
******
```

**Constraints:** `1 <= R, C <= 100`

---

### 4. **Right Angled Triangle**

**Input:**  
`N = 5`

**Output:**

```
*
**
***
****
*****
```

**Constraints:** `1 <= N <= 100`

---

### 5. **Inverted Right Angled Triangle**

**Input:**  
`N = 5`

**Output:**

```
*****
****
***
**
*
```

**Constraints:** `1 <= N <= 100`

---

### 6. **Pyramid Pattern**

**Input:**  
`N = 4`

**Output:**

```
   *
  ***
 *****
*******
```

**Constraints:** `1 <= N <= 100`

---

### 7. **Inverted Pyramid Pattern**

**Input:**  
`N = 4`

**Output:**

```
*******
 *****
  ***
   *
```

**Constraints:** `1 <= N <= 100`

---

### 8. **Right Angled Triangle with Numbers**

**Input:**  
`N = 5`

**Output:**

```
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
```

**Constraints:** `1 <= N <= 100`

---

### 9. **Floyd’s Triangle**

**Input:**  
`N = 5`

**Output:**

```
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
```

**Constraints:** `1 <= N <= 100`

---

### 10. **Diamond Pattern**

**Input:**  
`N = 3`

**Output:**

```
  *
 ***
*****
 ***
  *
```

**Constraints:** `1 <= N <= 50`

---

### 11. **Right Angled Triangle II (Alphabets)**

**Input:**  
`N = 5`

**Output:**

```
A
A B
A B C
A B C D
A B C D E
```

**Constraints:** `1 <= N <= 26`

---

### 12. **Sandglass Pattern**

**Input:**  
`N = 4`

**Output:**

```
********
 ******
  ****
   **
   **
  ****
 ******
********
```

**Constraints:** `1 <= N <= 50`

---

### 13. **Hollow Right Triangle**

**Input:**  
`N = 5`

**Output:**

```
*
**
* *
*  *
*****
```

**Constraints:** `2 <= N <= 100`

---

### 14. **Hollow Inverted Right Triangle**

**Input:**  
`N = 5`

**Output:**

```
*****
*  *
* *
**
*
```

**Constraints:** `2 <= N <= 100`

---

### 15. **Number Pyramid Pattern**

**Input:**  
`N = 4`

**Output:**

```
   1
  1 2
 1 2 3
1 2 3 4
```

**Constraints:** `1 <= N <= 100`

---


## Functions practice questions

### 1. 🔥 **Celsius to Fahrenheit Converter**

**Description:**  
Convert temperature from Celsius to Fahrenheit using the formula:

> `F = (C × 9/5) + 32`

**Input:**  
`int C` — Temperature in Celsius

**Output:**  
`float` — Temperature in Fahrenheit (rounded to 2 decimal places)

**Constraints:**

- `-100 <= C <= 100`
    

**Sample Input:**

```
25
```

**Expected Output:**

```
77.00
```

---

### 2. 📐 **Area of a Rectangle**

**Description:**  
Calculate the area of a rectangle using the formula:

> `Area = Length × Breadth`

**Input:**  
`int L, B` — Length and Breadth of the rectangle

**Output:**  
`int` — Area of the rectangle

**Constraints:**

- `1 <= L, B <= 10^4`
    

**Sample Input:**

```
15 10
```

**Expected Output:**

```
150
```

---

### 3. 🚗 **Distance Covered by a Vehicle**

**Description:**  
Calculate the distance covered using the formula:

> `Distance = Speed × Time`

**Input:**  
`int speed, int time`

**Output:**  
`int` — Total distance in km

**Constraints:**

- `1 <= speed <= 300`
    
- `1 <= time <= 24`
    

**Sample Input:**

```
60 5
```

**Expected Output:**

```
300
```

---

### 4. 🏗️ **Number of Rounds of Lift**

**Description:**  
Given the total number of people `P` and lift capacity `C`, calculate the minimum number of rounds the lift needs to make to carry all people.

**Input:**  
`int P, int C`

**Output:**  
`int` — Minimum number of rounds required

**Constraints:**

- `1 <= P <= 10^5`
    
- `1 <= C <= 100`
    

**Sample Input:**

```
27 8
```

**Expected Output:**

```
4
```

_Explanation:_  
8 + 8 + 8 + 3 → 4 rounds

---

### 5. 📈 **Line Equation (y = mx + c)**

**Description:**  
Given values of `m`, `x`, and `c`, compute the value of `y` using:

> `y = m * x + c`

**Input:**  
`int m, x, c`

**Output:**  
`int` — Computed value of `y`

**Constraints:**

- `-10^3 <= m, x, c <= 10^3`
    

**Sample Input:**

```
2 4 3
```

**Expected Output:**

```
11
```

---


## In-built Data Structure Practice Questions

- **Title**
- **Problem Statement**
- **Input Format**
- **Output Format**
- **Constraints**
- **Sample Input/Output**
- **Expected Output**

---

### 1. ✅ **Sum of List Elements**

**Description:**  
Calculate the sum of all elements in a list.

**Input:**  
`List[int] nums`

**Output:**  
`int` — Sum of elements

**Constraints:**

- `1 <= len(nums) <= 10^4`
    
- `-10^6 <= nums[i] <= 10^6`
    

**Sample Input:**  
`[1, 2, 3, 4, 5]`

**Expected Output:**  
`15`

---

### 2. ✅ **Largest Element in a List**

**Description:**  
Return the largest number in the list.

**Input:**  
`List[int] nums`

**Output:**  
`int` — Maximum element

**Constraints:**

- `1 <= len(nums) <= 10^4`
    

**Sample Input:**  
`[4, 17, 9, 1]`

**Expected Output:**  
`17`

---

### 3. ✅ **Remove Duplicates in a List**

**Description:**  
Remove all duplicate values from a list while preserving order.

**Input:**  
`List[int] nums`

**Output:**  
`List[int]` — List without duplicates

**Constraints:**

- `1 <= len(nums) <= 10^4`
    

**Sample Input:**  
`[1, 2, 2, 3, 1]`

**Expected Output:**  
`[1, 2, 3]`

---

### 4. ✅ **Check if All Elements in a List are Unique**

**Description:**  
Check if a list contains all unique values.

**Input:**  
`List[int] nums`

**Output:**  
`bool` — `True` if all elements are unique, else `False`

**Constraints:**

- `1 <= len(nums) <= 10^5`
    

**Sample Input:**  
`[1, 2, 3, 4]`

**Expected Output:**  
`True`

---

### 5. ✅ **Program to Reverse a List**

**Description:**  
Return the reversed list.

**Input:**  
`List[Any] items`

**Output:**  
`List[Any]` — Reversed list

**Sample Input:**  
`[1, 2, 3, 4]`

**Expected Output:**  
`[4, 3, 2, 1]`

---

### 6. ✅ **Count Number of Odd and Even Elements in a List**

**Description:**  
Count and return how many elements are odd and how many are even.

**Input:**  
`List[int] nums`

**Output:**  
`Tuple[int, int]` — (odd_count, even_count)

**Sample Input:**  
`[1, 2, 3, 4, 5]`

**Expected Output:**  
`(3, 2)`

---

### 7. ✅ **Maximum Difference Between Two Consecutive Elements**

**Description:**  
Find the max absolute difference between any two consecutive elements.

**Input:**  
`List[int] nums`

**Output:**  
`int`

**Sample Input:**  
`[2, 9, 4, 1, 7]`

**Expected Output:**  
`7`

---

### 8. ✅ **Merge Two Sorted Lists**

**Description:**  
Merge two sorted lists into a single sorted list.

**Input:**  
`List[int] list1, List[int] list2`

**Output:**  
`List[int]` — Sorted merged list

**Sample Input:**  
`[1, 3, 5], [2, 4, 6]`

**Expected Output:**  
`[1, 2, 3, 4, 5, 6]`

---

### 9. ✅ **Rotate a List**

**Description:**  
Rotate the list `k` times to the right.

**Input:**  
`List[int] nums, int k`

**Output:**  
`List[int]`

**Sample Input:**  
`[1, 2, 3, 4, 5], k = 2`

**Expected Output:**  
`[4, 5, 1, 2, 3]`

---

### 10. ✅ **Merge 2 Lists into Dictionary**

**Description:**  
Given two lists of equal length, create a dictionary with keys from first and values from second.

**Input:**  
`List[str] keys, List[Any] values`

**Output:**  
`Dict[str, Any]`

**Sample Input:**  
`['a', 'b', 'c'], [1, 2, 3]`

**Expected Output:**  
`{'a': 1, 'b': 2, 'c': 3}`

---

### 11. ✅ **Merge Multiple Dictionaries**

**Description:**  
Merge all provided dictionaries into one. Later keys overwrite earlier ones.

**Input:**  
`List[Dict] dicts`

**Output:**  
`Dict` — Merged dictionary

**Sample Input:**  
`[{'a': 1}, {'b': 2}, {'a': 3}]`

**Expected Output:**  
`{'a': 3, 'b': 2}`

---

### 12. ✅ **Word Frequency in a Sentence**

**Description:**  
Count frequency of each word in a given string.

**Input:**  
`str sentence`

**Output:**  
`Dict[str, int]`

**Sample Input:**  
`"this is a test this is"`

**Expected Output:**  
`{'this': 2, 'is': 2, 'a': 1, 'test': 1}`

---

### 13. ✅ **Palindromic Tuple**

**Description:**  
Given a tuple of strings, return only palindromic elements.

**Input:**  
`Tuple[str] items`

**Output:**  
`List[str]` — Palindromes only

**Sample Input:**  
`('madam', 'racecar', 'hello')`

**Expected Output:**  
`['madam', 'racecar']`

---

### 14. ✅ **Merge Dictionaries with Common Keys**

**Description:**  
Merge dictionaries by summing values of common keys.

**Input:**  
`List[Dict[str, int]] dicts`

**Output:**  
`Dict[str, int]`

**Sample Input:**  
`[{'a': 1, 'b': 2}, {'a': 3, 'c': 4}]`

**Expected Output:**  
`{'a': 4, 'b': 2, 'c': 4}`

---

### 15. ✅ **Check if List is Subset of Another List**

**Description:**  
Return `True` if all elements of list A exist in list B.

**Input:**  
`List[int] A, List[int] B`

**Output:**  
`bool`

**Sample Input:**  
`[1, 2], [1, 2, 3, 4]`

**Expected Output:**  
`True`

---


## Mathematical Practice Questions

### 1. ✅ **Sum of N Even Natural Numbers**

**Description:**  
Calculate the sum of the first `N` even natural numbers.

**Input:**  
`int N`

**Output:**  
`int` — Sum of the first `N` even numbers

**Constraints:**

- `1 <= N <= 10^5`
    

**Sample Input:**  
`5`

**Expected Output:**  
`30`

_Explanation:_ Even numbers = 2 + 4 + 6 + 8 + 10 = 30

---

### 2. ✅ **Check for Even Number**

**Description:**  
Check if a number is even.

**Input:**  
`int num`

**Output:**  
`bool` — `True` if even, else `False`

**Constraints:**

- `-10^9 <= num <= 10^9`
    

**Sample Input:**  
`7`

**Expected Output:**  
`False`

---

### 3. ✅ **Check for Prime Number**

**Description:**  
Check whether a number is prime.

**Input:**  
`int num`

**Output:**  
`bool` — `True` if prime, else `False`

**Constraints:**

- `0 <= num <= 10^6`
    

**Sample Input:**  
`13`

**Expected Output:**  
`True`

---

### 4. ✅ **Valid Perfect Square**

**Description:**  
Determine whether a number is a perfect square.

**Input:**  
`int num`

**Output:**  
`bool` — `True` if perfect square, else `False`

**Constraints:**

- `0 <= num <= 10^10`
    

**Sample Input:**  
`36`

**Expected Output:**  
`True`

---

### 5. ✅ **Decimal to Binary**

**Description:**  
Convert a non-negative integer to binary (without using built-in `bin()`).

**Input:**  
`int num`

**Output:**  
`str` — Binary representation

**Constraints:**

- `0 <= num <= 10^9`
    

**Sample Input:**  
`10`

**Expected Output:**  
`1010`

---

### 6. ✅ **Binary to Decimal**

**Description:**  
Convert a binary string to its decimal equivalent.

**Input:**  
`str binary`

**Output:**  
`int` — Decimal representation

**Constraints:**

- `1 <= len(binary) <= 32`
    
- Binary contains only `'0'` or `'1'`
    

**Sample Input:**  
`"1010"`

**Expected Output:**  
`10`

---

### 7. ✅ **GCD of Two Numbers**

**Description:**  
Find the Greatest Common Divisor (GCD) of two numbers.

**Input:**  
`int a, int b`

**Output:**  
`int` — GCD of `a` and `b`

**Constraints:**

- `1 <= a, b <= 10^9`
    

**Sample Input:**  
`20 28`

**Expected Output:**  
`4`

---


## String Practice Questions

### 1. 🔁 **Reverse a String**

**Description:**  
Reverse the characters of the given string.

**Input:**  
`str s`

**Output:**  
`str` — Reversed string

**Constraints:**

- `1 <= len(s) <= 10^5`
    

**Sample Input:**  
`"hello"`

**Expected Output:**  
`"olleh"`

---

### 2. 🔡 **Count Vowels in a String**

**Description:**  
Count the number of vowels (`a, e, i, o, u`) in the string.

**Input:**  
`str s`

**Output:**  
`int` — Number of vowels

**Constraints:**

- `1 <= len(s) <= 10^5`
    

**Sample Input:**  
`"education"`

**Expected Output:**  
`5`

---

### 3. 🔍 **Check for Same Strings**

**Description:**  
Return `True` if two strings are exactly the same, case-sensitive.

**Input:**  
`str s1, str s2`

**Output:**  
`bool`

**Constraints:**

- `1 <= len(s1), len(s2) <= 10^5`
    

**Sample Input:**  
`"OpenAI", "OpenAI"`

**Expected Output:**  
`True`

---

### 4. 🔄 **Check Palindrome**

**Description:**  
Check whether the given string is a palindrome (reads the same backward).

**Input:**  
`str s`

**Output:**  
`bool`

**Constraints:**

- `1 <= len(s) <= 10^5`
    

**Sample Input:**  
`"racecar"`

**Expected Output:**  
`True`

---

### 5. 📝 **Count Words in a String**

**Description:**  
Return the number of words in a sentence (words separated by whitespace).

**Input:**  
`str sentence`

**Output:**  
`int`

**Constraints:**

- `1 <= len(sentence) <= 10^5`
    

**Sample Input:**  
`"This is a test"`

**Expected Output:**  
`4`

---

### 6. 🔁 **Remove Duplicates in a String**

**Description:**  
Return the string with all duplicate characters removed, preserving the first occurrence.

**Input:**  
`str s`

**Output:**  
`str`

**Constraints:**

- `1 <= len(s) <= 10^5`
    

**Sample Input:**  
`"banana"`

**Expected Output:**  
`"ban"`

---

### 7. 🧮 **Count Consonants in a String**

**Description:**  
Return the number of consonants in the given string. Ignore spaces and vowels.

**Input:**  
`str s`

**Output:**  
`int`

**Constraints:**

- `1 <= len(s) <= 10^5`
    

**Sample Input:**  
`"hello world"`

**Expected Output:**  
`7`

---

### 8. 🔄 **Check for Anagrams**

**Description:**  
Check if two strings are anagrams (same characters, different order).

**Input:**  
`str s1, str s2`

**Output:**  
`bool`

**Constraints:**

- `1 <= len(s1), len(s2) <= 10^5`
    

**Sample Input:**  
`"listen", "silent"`

**Expected Output:**  
`True`

---

### 9. ✅ **Check Subsequence**

**Description:**  
Check if `s1` is a subsequence of `s2`.

**Input:**  
`str s1, str s2`

**Output:**  
`bool`

**Constraints:**

- `1 <= len(s1), len(s2) <= 10^5`
    

**Sample Input:**  
`"abc", "aebdc"`

**Expected Output:**  
`True`

---

### 10. 🔎 **Check for Substring**

**Description:**  
Check if one string is a substring of another.

**Input:**  
`str small, str large`

**Output:**  
`bool`

**Constraints:**

- `1 <= len(small), len(large) <= 10^5`
    

**Sample Input:**  
`"test", "this is a test string"`

**Expected Output:**  
`True`

---

### 11. 📏 **Length of the Longest Word**

**Description:**  
Return the length of the longest word in a sentence.

**Input:**  
`str sentence`

**Output:**  
`int`

**Constraints:**

- `1 <= len(sentence) <= 10^5`
    

**Sample Input:**  
`"The quick brown fox jumps"`

**Expected Output:**  
`5`  
(_"quick" or "jumps"_)