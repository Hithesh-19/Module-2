# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
try:
    a=int(input())
except ValueError:
    print("Invalid input")
else:
    for i in range(a):
        for j in range(a-i-1):
            print(" ",end="")
        c=1
        for k in range(i+1):
            print(c,end=" ")
            c=c*(i-k)//(k+1)
        print()
```



## Sample Output

<img width="1920" height="1080" alt="Screenshot 2025-10-20 205228" src="https://github.com/user-attachments/assets/29b8cfd0-601d-4bc4-97f3-64c3fa7804b5" />


## Result
Thus the Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user executed successfully.
