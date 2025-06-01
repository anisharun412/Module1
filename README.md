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
num=int(input())
if(num%2==0):
      print("Even")
else:
    print("Odd")
```    
## Output

![image](https://github.com/user-attachments/assets/28a73369-7134-4c96-90f2-523ffe6a5ba9)


## Result
Thus the program has been successfully executed


# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = (0 == True)
b = (False== False)
c = True + True
d = False + 9
print('a is',a)
print('b is',b)
print('c:',c)
print('d:',d)
```
## Output

![image](https://github.com/user-attachments/assets/a95f995d-de21-477f-88e3-72e93f0f12df)


## Result
Thus, the program as been excuted successfully.

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
v='T'
b='a'
print(v)
print(b)
```

## Output

![image](https://github.com/user-attachments/assets/a13832cf-f17d-47be-8026-165f48bc6701)

## Result
Thus, the program is executed sucessfully.

# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.


## 💻 Program
```
x=int(input(''))
y=int(input(''))
x=complex(x,y)
print(x)
print(x.real)
print(x.imag)
```
## Output

![image](https://github.com/user-attachments/assets/fc2312f5-1f70-41e9-80f8-eef3403ef69e)

## Result
Thus, the program as been executed successfully.

# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `line`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
line=input()
print(line)
```
## Output

![image](https://github.com/user-attachments/assets/86c44735-f428-4e42-9cd5-e6634f6fe71b)

## Result
Thus the program is executed successfully
