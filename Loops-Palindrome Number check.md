## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
~~~
num = int(input("Enter a number: "))
temp = num
rev = 0

while temp > 0:
    rev = (rev * 10) + (temp % 10)
    temp = temp // 10

if num == rev:
    print(num, "is a palindrome number.")
else:
    print(num, "is not a palindrome number.")
~~~
## Output
<img width="1671" height="987" alt="530356121-82ff5715-fb7b-4e45-aa33-e09c51d18876" src="https://github.com/user-attachments/assets/b45a77e8-afa9-413d-88b7-1dc5ae13d4bd" />

## Result
The program successfully checks whether a given number is a palindrome using loops.
