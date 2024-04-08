# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```

Program to find the square root for the given number(newton's method) using function.
Developed by: KEERTHIVASAN M
RegisterNumber: 212223100021 

def newton_sqrt(number, tolerance=1e-10):

    x = number  # Initial guess
    while True:
        next_x = 0.5 * (x + number / x)  # Newton's method
        if abs(next_x - x) < tolerance:
            return next_x
        x = next_x

# Example usage
number = int(input())
square_root = newton_sqrt(number)
print("Square root of the number: {}".format(square_root))

```

## Output:

![Screenshot 2024-03-17 130408](https://github.com/rdxkeerthi/Square-root-of-a-number/assets/147473120/3500018e-6963-4d9f-a92c-19d3cf8d616f)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
