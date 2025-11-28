# 9)a) List Comprehension:Generates all odd numbers between 500 and 600
##  AIM:
To write a Python class-based program that generates all odd numbers between 500 and 600 using **list comprehension**, and stores them in a list.



#  ALGORITHM:

1. **Start**
2. Create a class named `Generate`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store odd numbers
6. Print the resulting list of odd numbers
7. **Stop**



#  PROGRAM:

```
class Generate:
    def _init_(self,first,d,last):
        self.first=first
        self.d=d
        self.last=last
    def Ap_generate(self):
        L=[i for i in range(self.last-1,self.first,self.d)]
        return L
        
Series = Generate(500,-2,600)
print(Series.Ap_generate())
```

## OUTPUT:
![list-odd](https://github.com/user-attachments/assets/e1eb77ae-75e4-4887-a0fd-7b75cf8f4aa7)


## RESULT:
Thus a Python class-based program that generates all odd numbers between 500 and 600 using **list comprehension**, and stores them in a list is created.

