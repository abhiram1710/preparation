1. Python/01-Basics.md
# Python Basics — Day 1

## 1. Variables

Variables store values.

```python
name = "Abhiram"
age = 20
marks = 85.5

Python automatically determines the data type.

Common data types
int → 10
float → 10.5
str → "Hello"
bool → True / False
2. Input

input() takes input from the user.

name = input()

Input is received as a string.

For numbers:

age = int(input())

Example:

a = int(input())
b = int(input())

print(a + b)
3. Conditions

Used to make decisions.

age = 20

if age >= 18:
    print("Eligible")
else:
    print("Not Eligible")
if / elif / else
marks = 75

if marks >= 90:
    print("A")
elif marks >= 60:
    print("B")
else:
    print("C")
4. Operators
Comparison
== Equal
!= Not equal
> Greater than
< Less than
>= Greater than or equal
<= Less than or equal
Logical
and → both conditions must be true
or → at least one condition must be true
not → reverses the condition
5. for Loop

Used to repeat code.

for i in range(5):
    print(i)

Output:

0
1
2
3
4

Important

range(5) means 0 to 4.

6. while Loop
i = 1

while i <= 5:
    print(i)
    i += 1