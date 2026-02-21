MAITREYEE UPADHYAY 25070123071

# AIM:

To study and implement the while loop in Python.

# THEORY:

A while loop in Python is used to execute a block of code repeatedly as long as a given condition is true. It is mainly used when the number of iterations is not known in advance.
Syntax:

while condition:
    statements

Types of loops in Python:

-While Loop
-For Loop
-Nested Loop

The while loop checks the condition first. If the condition is true, the statements inside the loop execute repeatedly until the condition becomes false.

# Algorithms 

# 1. Print numbers from 1 to 5

1. Start
2. Initialize `i = 1`
3. Check if `i ≤ 5`
4. Print `i`
5. Increase `i` by 1
6. Repeat steps until condition becomes false
7. Stop

# 2. Print numbers from 1 to n

1. Start
2. Input number `n`
3. Initialize `i = 1`
4. While `i ≤ n`, print `i`
5. Increment `i`
6. Stop when condition becomes false

# 3. Factorial of a number

1. Start
2. Input number `n`
3. Initialize `fact = 1`
4. Multiply `fact` by `n`
5. Decrease `n` by 1
6. Repeat until `n > 0`
7. Display factorial
8. Stop

# 4. Fibonacci Series

1. Start
2. Input number of terms `n`
3. Initialize `a = 0`, `b = 1`
4. Print `a`
5. Calculate next term `c = a + b`
6. Update `a = b`, `b = c`
7. Repeat until required terms printed
8. Stop

# 5. Fibonacci series within a limit

1. Start
2. Input limit
3. Initialize `a = 0`, `b = 1`
4. Print `a` while `a ≤ limit`
5. Update numbers using `a, b = b, a + b`
6. Stop

# 6. Reverse of a number

1. Start
2. Input number
3. Initialize `rev = 0`
4. Get last digit using modulus
5. Add digit to reversed number
6. Remove last digit from original number
7. Repeat until number becomes 0
8. Print reversed number
9. stop

# 7. Palindrome number

1. Start
2. Input number
3. Reverse the number using loop
4. Compare original number with reversed number
5. If equal → Palindrome
6. Else → Not palindrome
7. Stop

# 8. Palindrome string using loop

1. Start
2. Take a string
3. Compare first and last characters
4. Move inward step by step
5. If mismatch occurs → Not palindrome
6. Otherwise → Palindrome
7. Stop

# 9. Palindrome string using slicing

1. Start
2. Input string
3. Reverse string using slicing
4. Compare original and reversed string
5. Print result
6. Stop

# 10. Count digits in a number

1. Start
2. Input number
3. Initialize `count = 0`
4. Divide number by 10 repeatedly
5. Increase count each time
6. Stop when number becomes 0
7. Print count

# 11. Search element in a list

1. Start
2. Create list
3. Input element to search
4. Compare each element using loop
5. If found → Display index
6. If not found → Display message
7. Stop

# 12. Print odd numbers from 1 to 10

1. Start
2. Initialize `i = 0`
3. Increase `i` by 1 each iteration
4. Check if number is even
5. If even → skip using continue
6. Print odd numbers
7. Stop

## Conclusion

In this experiment, we studied the while loop in Python and implemented various programs such as number printing, factorial calculation, Fibonacci series, palindrome checking, digit counting, and searching elements. 
