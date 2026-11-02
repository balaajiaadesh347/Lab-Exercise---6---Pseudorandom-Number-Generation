# Lab-Exercise---6---Pseudorandom-Number-Generation

**AIM:**

Implementation of Pseudorandom Number Generation Using Standard library

**ALGORITHM:**

Start the program and import the required libraries. Seed the random number generator using the current time(i.e) rand(time(0)); Get the number of randon number to generate. Pass the value for number of iterations and print the numbers. End the program.

**PROGRAM:**
```
 import random

minimum = int(input("Enter minimum value: "))
maximum = int(input("Enter maximum value: "))

numbers = list(range(minimum, maximum + 1))

random.shuffle(numbers)

print("Random numbers between", minimum, "and", maximum, "are:")

for num in numbers:
    print(num, end=" ")
```

**OUTPUT:**

<img width="722" height="262" alt="image" src="https://github.com/user-attachments/assets/4fbefda2-5420-45ec-b58e-be94e0edd034" />


**RESULT:**

Thus, the Python program for implementing Pseudorandom Number Generation using the standard library was executed successfully.

