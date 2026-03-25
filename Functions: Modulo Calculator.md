# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
~~~
def result(a, b):
    print("The modulo of", a, "and", b, "is:", a % b)
x = int(input("Enter the first number: "))
y = int(input("Enter the second number: "))
result(x, y)
~~~

## Output
<img width="1554" height="993" alt="530354923-b34dc35a-3e40-4f49-869f-c74ad5896c8f" src="https://github.com/user-attachments/assets/848274d2-c95b-460d-a11e-fbf2d8e21d8f" />

## Result
The program successfully defines a function to calculate and display the modulo of two numbers using the % operator.
