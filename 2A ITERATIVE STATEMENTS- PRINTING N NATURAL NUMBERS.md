# Exp.No:2(a) ITERATIVE STATEMENTS- PRINTING DIVISIBLE BY 11 NUMBERS

# AIM
To create a print numbers range from M to N (including M and N values) divisible by 11 in reverse order.

# ALGORITHM
Start

Read integer a from the user.

Read integer b from the user.

Loop from i = b down to a (inclusive):

Use a for loop: for i in range(b, a - 1, -1)

Check if the current number i is divisible by 11:

If i % 11 == 0, then:

Print i

End

# PROGRAM
```
a=int(input())
b=int(input())
for i in range(b,a-1,-1):
    if i%11==0:
        print(i)
```
# OUTPUT
<img width="337" height="403" alt="image" src="https://github.com/user-attachments/assets/64a4594c-829a-4c85-945c-2d6ed388e548" />


# RESULT
Thus the python program for print numbers range from M to N (including M and N values) divisible by 11 in reverse order has been implemented and executed successfully.
