# Exp.No:2(d) LOOPING PATTERNS- PRINTING PATTERN

# AIM
To write a program to print inverted pyramid pattern with the same digit.

# ALGORITHM
Start

Read integer a from the user

Loop from i = a down to 1 (inclusive):

for i in range(a, 0, -1)

Inside the outer loop, loop from j = 0 to i - 1:

for j in range(0, i)

Print the value of a followed by a space (keep on same line)

Print a newline after the inner loop to move to the next row

End

# PROGRAM
```
a=int(input())
for i in range(a,0,-1):
    for j in range (0,i):
        print(a,end=" ")
    print()
```
# OUTPUT
<img width="451" height="529" alt="image" src="https://github.com/user-attachments/assets/e85a2a27-37ae-439f-8dde-b91de54c27e6" />


# RESULT
Thus the python program to program to print inverted pyramid pattern with the same digit has been implemented and executed successfully.
