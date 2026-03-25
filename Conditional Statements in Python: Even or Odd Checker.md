# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```py
a = int(input())

# Step 2: Check using modulo operator
if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```


## Output
<img width="624" height="237" alt="image" src="https://github.com/user-attachments/assets/5cbb7177-cecc-428b-bc38-5bc44a4b7a12" />


## Result
The program successfully checks whether a given number is even or odd using an if...else conditional statement and the modulo (%) operator.
