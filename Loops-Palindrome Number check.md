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

rev=0

tem=num

while tem>0:

    rev=(10*rev)+tem%10
    
    tem//=10

if (rev==num):

    print(f"The given number {num} is a Palindrome")
    
else:

    print(f"The given number {num} is not a palindrome")



## Output

![440391105-635b6558-b39f-4bd2-985a-55b5c0ee42f2](https://github.com/user-attachments/assets/69d53c04-daa1-4fcd-84f8-627cdb381ad0)


## Result

Thus the program that checks whether a given number is a palindrome using loops is executed successfully.
