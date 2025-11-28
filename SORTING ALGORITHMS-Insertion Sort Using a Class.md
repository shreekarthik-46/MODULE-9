# 9)e) SORTING ALGORITHMS: Insertion Sort Using a Class

This program demonstrates how to implement the **Insertion Sort algorithm** using a Python class. It allows the user to input a list of numbers, sorts them using the insertion sort technique, and displays the sorted list.



##  Aim

To develop a Python class with functions to:
 Create a list of integers
 Sort it using the **Insertion Sort** algorithm
 Display the sorted list



##  Algorithm

1. **Start the program**
2. **Define a class** `InsertionSorter`
3. Inside the class:
   - `create_list()`:
     - Read number of elements
     - Store them in a list
   - `insertion_sort()`:
     - Iterate from the second element to the end
     - Move elements greater than the key to one position ahead
     - Insert the key at the correct position
   - `print_list()`:
     - Print the sorted list
4. **Create an object** of the class
5. **Call** the methods in order: `create_list()`, `insertion_sort()`, and `print_list()`
6. **End the program**



##  PROGRAM:
```
def create_list(n):
    L=[]
    for i in range(n):
        L.append(int(input()))
    return L

def insertion_sort(L):
    for i in range(len(L)):
        j=i
        while(L[j-1]>L[j] and j>0):
            L[j-1],L[j]=L[j],L[j-1]
            j-=1
    return L
def print_list(L):
    for i in range(len(L)):
        print(L[i])
        
n=int(input())
L=create_list(n)
print("Before Sorting")
print_list(L)
```
    


## OUTPUT:
![insertion sort](https://github.com/user-attachments/assets/58853f44-12b9-4905-8a85-92c992f1cfc3)


## RESULT:
Thus a Python class with functions to:
Create a list of integers
Sort it using the **Insertion Sort** algorithm
Display the sorted list is developed
