## NAME : VIGNESH R
## REG NO : 212225030031

# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

```
x=16
y=bin(x)
print(y)
```

## Output

<img width="741" height="396" alt="Screenshot 2026-05-31 155231" src="https://github.com/user-attachments/assets/ab2dfea2-cd24-48c6-acd0-4a14faf52ebe" />


## Result

Thus, the program to perform Binary Conversion using Built-in Functions in Python was executed successfully.


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
```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```

## Output

<img width="816" height="392" alt="517994929-22fe8612-80e0-43d4-86fc-c1378352f088" src="https://github.com/user-attachments/assets/9858ffea-ff78-46fa-9cce-69c24e2ee9cb" />

## Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.


# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
i=int(input())
j=int(input())
z=int(input())
f = lambda a, b,c: a+b+c
print(f(i, j,z))
```

## Output

<img width="617" height="452" alt="517995636-ad852486-5926-4eec-92fc-5be70a4b0910" src="https://github.com/user-attachments/assets/bce20250-dae0-4ce0-a245-d88e651acfc7" />

## Result
Thus,the Python program that defines a lambda function which takes two arguments a , b and c, and returns their sum is created successfully.


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
```
rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
```
## Sample Output

<img width="611" height="683" alt="517996248-1feb811d-de3b-4e61-94cb-7c4a290c8cdd" src="https://github.com/user-attachments/assets/2a7d101e-5592-42e6-9976-a5ab1fc9003b" />

## Result
Thus,the Python program that defines a lambda function which takes two arguments a , b and c, and returns their sum is created successfully.


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
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```

## Output

<img width="965" height="242" alt="517997532-f55253c7-9683-496e-a194-77fb1c6a0e67" src="https://github.com/user-attachments/assets/b6ed1c45-713d-4689-8e6a-1b4c64a96063" />

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.

