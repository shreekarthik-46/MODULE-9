#  List Comprehension:Transpose of Matrix 

##  AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

##  ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

##  PROGRAM:
```
def read_matrix(r,c):
    matrix=[[0]*c for row in range(r)]
    for i in range(r):
        lines=list(map(int, input().split()))
        for j in range(c):
            matrix[i][j]=lines[j]
    return matrix
def print_matrix(M):
    print("Matrix:")
    for i in range(len(M)):
        for j in range(len(M[0])):
            print(M[i][j],end=" ")
        print()
def transpose(M):
    result=[[0]* len(M)for rows in range(len(M[0]))]
    for i in range(len(M)):
        for j in range(len(M[0])):
            result[j][i]=M[i][j]
    return result
```

## OUTPUT:
![transpose](https://github.com/user-attachments/assets/d28289f0-b5a5-41bf-a16c-d608825a1c4a)



## RESULT:
Thus a Python program to compute the **transpose** of a matrix using **list comprehension** is created.


