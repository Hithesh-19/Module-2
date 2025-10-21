## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
temp=num
rev=0
while temp>0:
    rev=(10*rev)+(temp%10)
    temp=temp//10
if rev==num:
    print(num,"is a palindrome")
else:
    print(num,"is not a palindrome")
    
```
## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-20 212140" src="https://github.com/user-attachments/assets/11bd7148-2dfc-4776-bb6e-d9bd2647526d" />


## Result
Thus the Python program that checks whether a given number is a **palindrome** using loops executed successfully.
