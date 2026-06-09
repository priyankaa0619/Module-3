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
s = "google"


reversed_s = s[::-1]


if s == reversed_s:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```
## Output
<img width="1019" height="235" alt="Screenshot 2025-10-18 233731" src="https://github.com/user-attachments/assets/654cd810-51a7-441e-9301-02df28330e7e" />

## Result
The a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is executed successfully.
