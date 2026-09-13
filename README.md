# Python-While_Loop

This repository contains hands-on Python exercises focused on understanding and practicing **while loops**, including the use of **break** and **continue** statements.

The exercises helped me strengthen my understanding of loop conditions, user input, arithmetic operations, list indexing, and logical problem-solving in Python.

---

## 📌 Topics Covered

- While Loop
- Infinite Loop (`while True`)
- Break Statement
- Continue Statement
- Conditional Statements
- User Input
- Arithmetic Operators
- List Indexing
- Factorial
- Fibonacci Sequence
- Number Reversal

---

## 🔹 Basic While Loop – 10 Exercises

1. Print numbers from 1 to 10.
2. Print all even numbers between 1 and 50.
3. Print the sum of numbers from 1 to 100.
4. Take user input repeatedly until they type `"exit"`.
5. Print the multiplication table of a given number.
6. Count the number of digits in a number.
7. Reverse a number entered by the user.
8. Find the factorial of a given number.
9. Print Fibonacci numbers less than 50.
10. Find the largest number in a list using a while loop.

---

## 🔹 While Loop with Break and Continue – 10 Exercises

1. Ask the user to enter numbers repeatedly and stop when they enter `0` using `break`.
2. Print numbers from 1 to 20 but skip `5` using `continue`.
3. Keep asking for a password until the correct password is entered.
4. Print numbers from 1 to 30 but skip multiples of `3`.
5. Print numbers from 1 to 15 but stop when the number becomes greater than `10`.
6. Take continuous user input and ignore negative numbers.
7. Print squares of numbers from 1 to 20 but stop when the square becomes greater than `100`.
8. Print numbers divisible by `4` between 1 and 50 but skip `16`.
9. Keep reading numbers until the sum exceeds `100`.
10. Print numbers from 1 to 20 but skip multiples of `5`.

---

## 💡 Key Concepts Learned

### While Loop

A `while` loop repeatedly executes a block of code as long as its condition remains `True`.

Example:

```
i = 1

while i <= 10:
    print(i)
    i += 1

```

### Break

The break statement immediately terminates the loop when a specified condition is satisfied.

```
while True:
    number = int(input("Enter a number (0 to stop): "))

    if number == 0:
        break

    print(number)
```

### Continue

The continue statement skips the remaining code in the current iteration and moves to the next iteration.

```
i = 1

while i <= 20:
    if i % 5 == 0:
        i += 1
        continue

    print(i)
    i += 1
```

## 🔢 Example – Factorial Using While Loop
```
number = int(input("Enter a number: "))

factorial = 1
i = 1

while i <= number:
    factorial = factorial * i
    i += 1

print("Factorial of", number, "is", factorial)
```

For example:

5! = 1 × 2 × 3 × 4 × 5 = 120

## 🔢 Example – Fibonacci Sequence Using While Loop
```
a = 0
b = 1

while a < 50:
    print(a)
    a, b = b, a + b
```

Output: 
0
1
1
2
3
5
8
13
21
34

---

## 🎯 Learning Outcomes

After completing these exercises, I gained a better understanding of:

✅ How while loops work in Python.

✅ How to control loops using conditions.

✅ How to use break to terminate a loop.

✅ How to use continue to skip an iteration.

✅ How to work with repeated user input.

✅ How to update loop variables correctly.

✅ How infinite loops can occur if loop variables are not updated properly.

✅ How to apply loops to practical problems such as factorials, Fibonacci sequences, digit counting, number reversal, and list operations.

---

## 🛠️ Technologies Used

Python 

Google Colab

Jupyter Notebook

---

⭐ This repository is part of my ongoing Python learning journey.


