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
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))
x = complex(a, b)
print("The complex number is:", x)
print("The real part of the complex number is:", x.real)
print("The imaginary part of the complex number is:", x.imag)
```


## Output
```
Enter the real part: 3
Enter the imaginary part: 4
The complex number is: (3+4j)
The real part of the complex number is: 3.0
The imaginary part of the complex number is: 4.0
```
## Result
Thus the given program is verified and executed sucessfully
