# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
N=input()
if N==N[::-1]:
  print("palindrone")
else:
  print("not palindrone")
```
## Output
<img width="915" height="205" alt="image" src="https://github.com/user-attachments/assets/f9d849ca-24da-475d-9dd5-c002979c52df" />

## Result
The program correctly checks and reports whether "google" is a palindrome by reversing the string manually
