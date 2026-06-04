##  2e)  Loops in Python: Number pattern

##  Aim
 To write a Python program to print the  simple number pattern using a for loop.Get the input for the number of rows 

##  Algorithm
1. Start

2. Input a number n.

3. For each number i from 1 to n−1:

4. Begin an inner loop.

5. For each number j from 1 to i:

6. Print the value of i on the same line.

7. After the inner loop ends, move to the next line.

8. Repeat until all rows are printed.

9. End

##  Program
```
n=int(input())
for i in range(1,n):
    for j in range(1,i+1):
        print(i,end=" ")
    print()
```
## Output
<img width="517" height="461" alt="image" src="https://github.com/user-attachments/assets/f083cbdd-b3db-4006-9dae-26061fbaae6c" />

## Result
Program executed Successfully.
