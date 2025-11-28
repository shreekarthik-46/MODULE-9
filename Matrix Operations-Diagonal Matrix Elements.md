# 9)c) Matrix Operations-Diagonal Matrix Elements Printer 

This Python program reads a matrix of any size from the user and prints **only the diagonal elements**, leaving other elements blank in the output.

##  Aim

To write a Python program that prints only the diagonal elements of a given matrix.

##  Algorithm

1. Read the number of rows and columns from the user.
2. Initialize an empty matrix of size `rows × columns`.
3. Populate the matrix with user input.
4. Display the full matrix.
5. Iterate through the matrix and:
   - If `i == j`, print the element (main diagonal).
   - Else, print a blank space.
6. Print a newline after each row.

##  Program
```
row=int(input())
col=int(input())
A=[]
for i in range(row):
    n=list(map(int,input().split()))
    A.append(n)
print(A)
for i in range(row):
    for j in range(col):
        if(i==j):
            print(A[i][j],end=" ")
        else:
            print(" ",end=" ")
    print()
```

### Output:

![diognal](https://github.com/user-attachments/assets/100837b0-d3e8-4890-8809-e7dc0dd53d74)

## Result
Thus a Python program that prints only the diagonal elements of a given matrix is created.

