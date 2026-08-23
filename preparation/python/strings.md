---

## 2. `Python/02-Strings.md`

```markdown
# Python Strings — Day 1

## 1. What is a String?

A string is a sequence of characters.

```python
s = "Cognizant"

Python uses zero-based indexing.

C o g n i z a n t
0 1 2 3 4 5 6 7 8

2. Indexing
s = "Cognizant"

print(s[0])    # C
print(s[-1])   # t

-1 represents the last character.

3. Length
s = "Python"

print(len(s))

Output:

6
4. Slicing
s = "Cognizant"

print(s[0:4])

Output:

Cogn
Rule

start is included.

end is excluded.

5. Reverse a String
s = "Python"

print(s[::-1])

Output:

nohtyP
Remember

[::-1] → reverse

6. Important String Methods
s.upper()
s.lower()
s.strip()
s.replace("old", "new")
s.split()

Example:

s = "I love Python"
print(s.split())

Output:

['I', 'love', 'Python']
7. Palindrome

A palindrome reads the same forward and backward.

Examples:

madam
level
racecar

Code:

s = input()

if s == s[::-1]:
    print("Palindrome")
else:
    print("Not Palindrome")
Placement Trick

Original == Reverse → Palindrome

Placement Focus

Must know:

Indexing
Negative indexing
Slicing
Reverse using [::-1]
len()
upper()
lower()
split()
Palindrome