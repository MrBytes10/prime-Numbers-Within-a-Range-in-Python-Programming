# Prime Number Checker within an Interval

This is a simple Python program to display all prime numbers within a given interval. The program checks each number in the specified range to determine if it is a prime number and prints all the prime numbers found.

## Getting Started

These instructions will help you run the prime number checker on your local machine.

### Prerequisites

You need to have Python installed on your computer. You can download and install Python from [python.org](https://www.python.org/downloads/).

### Running the Program

1. Clone the repository to your local machine:
   git clone https://github.com/MrBytes10/Prime-Number-Checker-in-Python.git
   cd Prime-Number-Checker-in-Python
   pen the `prime_number_checker.py` file and modify the `lower` and `upper` variables to set your desired range:

   lower = 100
   upper = 120

   - Run the script:
     python prime_number_checker.py

2. The program will output all the prime numbers within the specified range.

### Example

For example, with the range set from 100 to 120:
lower = 100
upper = 120

## The output will be:

    Prime numbers between 100 and 120 are
    101
    103
    107
    109
    113

- How It Works:
  The script works by iterating through each number in the specified range (lower to upper). For each number, it checks if the number has any divisors other than 1 and itself. If no divisors are found, the number is prime and is printed.

# Contributing

Feel free to submit issues or fork the repository and send pull requests. Contributions are welcome!

- Acknowledgments:
  This code is a basic implementation for educational purposes and to get started with prime number checking in Python.
