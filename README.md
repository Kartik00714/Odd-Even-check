Odd Even Check

This simple Python program takes two numbers as input, adds them, and determines whether the result is odd or even.

How It Works

The program asks the user to enter two numbers.

It adds both numbers.

It checks the sum using the modulus operator %.

If the sum is divisible by 2, it prints "Even", otherwise it prints "Odd".

Code Snippet
a = int(input("Enter first no.: "))
b = int(input("Enter second no.: "))
add = a + b
if add % 2 == 0:
    print("Even")
else:
    print("Odd")

How to Run

Make sure Python 3 is installed on your system.

Save the script as Odd_Even_check.py (or use your existing file).

Open a terminal or command prompt.

Run the program:

python Odd\ Even\ check.py


Enter two numbers when prompted.

Example
Enter first no.: 12
Enter second no.: 5
Odd

Requirements

Python 3.x
