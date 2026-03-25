# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
~~~
import math

rows = int(input("Enter number of rows: "))

for i in range(rows):
    print(" " * (rows - i), end=" ")
    for j in range(i + 1):
        print(math.comb(i, j), end=" ")
    print()
~~~

## Sample Output
<img width="1649" height="999" alt="530355870-fd036832-d574-4d91-a7a0-3f4e6c2912c7" src="https://github.com/user-attachments/assets/99903d21-2b30-4288-bd8a-7f0dfccbf402" />

## Result
The program successfully generates Pascal’s Triangle for the given number of rows using loops and the binomial coefficient formula.
