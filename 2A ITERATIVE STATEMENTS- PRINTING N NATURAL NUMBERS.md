# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING PRIME NUMBERS

###  Aim
To create a Python program for printing prime numbers using a `for` loop.

---

###  Algorithm

1. Begin the program.
2. Read the start and end values of the range from the user.
3. For each number in the range:
   3.1 If the number is greater than 1, check if it is prime.
       3.1.1 Divide the number by all integers from 2 to (number - 1).
       3.1.2 If divisible by any, it is not prime.
       3.1.3 If not divisible by any, it is prime → display the number.
4. End the program.


---

### 🧾 Program

```python
#Reg.NO:212223060188
#Name:k.nithiyasree
#Write your Code here
r=int(input())
for a in range(2,r+1):
    k=0
    for i in range(2,a//2+1):
        if(a%i==0):
            k=k+1
    if(k<=0):
        print(a)

```
### OUTPUT
<img width="477" height="677" alt="image" src="https://github.com/user-attachments/assets/2087b9a3-25d4-4e6e-9be5-4fe30f74086f" />

### RESULT
thus a Python program for printing prime numbers using a `for` loop has been executed successfully.



