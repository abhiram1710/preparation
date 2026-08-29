🧵 10. Strings

A string is a sequence of characters.

s = "hello"

Think:

Index:  0  1  2  3  4
        h  e  l  l  o
print(s[0])

Answer:

h
11. Length of String
s = "hello"

print(len(s))

Answer:

5
12. Reverse a String — Slicing
Problem
s = "hello"
Code
s = "hello"

reverse = s[::-1]

print(reverse)
Answer
olleh
Meaning
[start : stop : step]

[::-1] means:

Go through the entire string backwards.

13. Reverse String — Using Loop

This is more important for DSA understanding.

s = "hello"

reverse = ""

for i in range(len(s) - 1, -1, -1):
    reverse += s[i]

print(reverse)
Answer
olleh

The indexes are visited:

4 → 3 → 2 → 1 → 0

Therefore:

o → l → l → e → h
14. Palindrome

A palindrome reads the same forward and backward.

Example:

madam

Reverse:

madam
Simple code
s = "madam"

if s == s[::-1]:
    print("Palindrome")
else:
    print("Not Palindrome")
Answer
Palindrome
15. Count a Character
Problem
s = "programming"

Count 'g'.

Code
s = "programming"

count = 0

for ch in s:
    if ch == 'g':
        count += 1

print(count)
Answer
2
16. Count Vowels
Problem
s = "principal"
Code
s = "principal"

count = 0

for ch in s:
    if ch in "aeiou":
        count += 1

print(count)
Answer
3

The vowels are:

i, i, a