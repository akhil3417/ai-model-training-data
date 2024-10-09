
# Supervised Fine-Tuning (SFT) Prompt-Response Pairs

Below are examples of prompt-response pairs that would be used to fine-tune a language model on programming tasks.

## Example 1:
**Prompt:** Write a Python function to find the factorial of a number.

**Response:**
```python
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)
```

## Example 2:
**Prompt:** Write a Python function that finds the largest number in a list.

**Response:**

```python
Copy code
def find_largest(nums):
    if not nums:
        return None
    largest = nums[0]
    for num in nums[1:]:
        if num > largest:
            largest = num
    return largest
```

## Example 3:
 **Prompt:** Sort a list of dictionaries by the "age" key in Python.

 **Response:**

```python
Copy code
people = [
    {"name": "Alice", "age": 30},
    {"name": "Bob", "age": 25},
    {"name": "Charlie", "age": 35}
]

sorted_people = sorted(people, key=lambda person: person["age"])

```

This code sorts a list of dictionaries by the value associated with the "age" key using Python’s built-in sorted() function.

## Example 4:
 **Prompt:**Write a Python function to reverse a string.

**Response:**

```python
Copy code
def reverse_string(s):
    return s[::-1]
```

This function uses Python’s slicing feature to return the reversed version of the input string.


This content provides a range of prompt-response pairs that can be used to train a language model on common coding challenges.
