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
```
def even_number(n):
    if(n%2==0):
        print("EVEN")
    else:
        print("ODD")
        
n=int(input())
even_number(n)
```

## Output

![image](https://github.com/user-attachments/assets/42822f8d-36e8-4ba1-a1e7-8126094ed105)

## Result
