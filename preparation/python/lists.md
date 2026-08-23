
---

## 3. `Python/03-Lists.md`

```markdown
# Python Lists — Day 1

## 1. What is a List?

A list stores multiple values.

```python
numbers = [10, 20, 30, 40, 50]

Lists are ordered and mutable.

2. Access Elements
numbers = [10, 20, 30, 40, 50]

print(numbers[0])    # 10
print(numbers[-1])   # 50
3. List Slicing
print(numbers[1:4])

Output:

[20, 30, 40]

Remember:

Start included, end excluded.

4. Add Element
numbers.append(60)

Adds an element at the end.

5. Remove Element
numbers.remove(20)

Removes the value 20.

6. Sort
numbers.sort()

Sorts in ascending order.

For descending:

numbers.sort(reverse=True)
7. Reverse
numbers.reverse()

Reverses the list.

8. Length
len(numbers)

Returns the number of elements.

Placement Focus

Know:

Indexing
Slicing
append()
remove()
sort()
reverse()
len()
