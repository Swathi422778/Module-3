# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 9

---

### AIM  
To write a Python program to create a tuple containing all multiples of 9 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `9` up to `N - 1`, stepping by `9`.  
4. Return the tuple `multiples_of_9`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
tuple1=tuple()
a=int(input())
for i in range(9,a,9):
    tuple1=tuple1+(i,)
print(tuple1)
print("Length of the tuple is",len(tuple1))

```

### OUTPUT

![image](https://github.com/user-attachments/assets/74e4d00c-8f81-44f2-82f1-70cd7dfdf0d1)

### RESULT
Thus the Python program to create a tuple containing all multiples of 9 up to a given number **N** is successfully verified.

