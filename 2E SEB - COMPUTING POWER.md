# Exp.No:2e  
## SEB - Mirror Star Pattern

---

### AIM  
To Write a Python Program to print Right down Mirror Star Pattern .Get the input for number of rows as input.

---

### ALGORITHM
1. Begin the program.
2. Read the number of rows from the user.
3. For each row i from 1 to number of rows:
   3.1 Print (i-1) spaces.
   3.2 Print (rows - i + 1) stars.
4. Repeat until all rows are printed.
5. End the program.


---

### PROGRAM

```
rows = int(input())
i = rows
while i >= 1:
    j = rows
    while j > i:
      
        print(' ', end=' ')
        j -= 1
    k = 1
    while k <= i:
        print('*', end=' ')
        k += 1
    print()
    i -= 1
```
### OUTPUT
<img width="672" height="732" alt="image" src="https://github.com/user-attachments/assets/7df782a8-8e9e-4873-926f-fc7180c956a7" />

### RESULT
Thus a Python Program to print Right down Mirror Star Pattern .Get the input for number of rows as input has been executed successfully.
