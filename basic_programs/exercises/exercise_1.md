# Exercise 1

### Python program to add two numbers.

Given two numbers num1 and num2. The task is to write a Python program to find the addition of these two numbers.

#### Examples

```
num_a = 10, num_b = 20
Output: Sum of 10 and 20 is 30
```

### Option 1

```python
num_a = 10
num_b = 20

# Adding two numbers...
sum_numbers = num_a + num_b

# printing values
print("Sum of {0} and {1} is {2}" .format(num_a, num_b, sum_numbers))
```

### Option 2 - User input

```
First number: 13.5 Second number: 1.54
The sum of 13.5 and 1.54 is 15.04

```

```python
num_a = input("First number: ")
num_b = input("Second number: )"

# Adding two numbers...
sum_numbers = float(num_a) + float(num_b)

print("The sum of {0} and {1} is {2}" .format(num_a, num_b, sum_numbers))
```
