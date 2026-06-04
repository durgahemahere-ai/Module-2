#  2d)  Looping(Patterns)Reverse Pyramid of numbers Generator in Python

This project demonstrates a simple Python program to generate **Reverse Pyramid of numbers**, where the number of rows is provided by the user.

---

##  Aim

To write a Python program that generates **Reverse Pyramid of numbers** using numbers. The number of rows is accepted from the user.

---

##  Algorithm
1.Start

2.Input the number of rows (rows) from the user.

3.For each number i from 1 to rows−1:

4.Start an inner loop.

5.For each number j from i down to 1 (decreasing):

6.Print the value of j on the same line.

7.After the inner loop finishes, move to the next line.

8.End



---
##  Program
```
rows=int(input())
for i in range(1,rows):
    for j in range(i,0,-1):
        print(j,end=" ")
    print()
```

## Sample Output
<img width="534" height="455" alt="image" src="https://github.com/user-attachments/assets/7f416bb5-c36b-4cf3-af5f-8df1bf82bd5d" />

## Result
Program executed Successfully.
