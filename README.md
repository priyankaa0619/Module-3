# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```

numbers = [10, 20, 30, 40, 50]

total = 0
for num in numbers:
    total += num


print("The sum of all elements in the list is:", total)

```

## Output
<img width="1044" height="338" alt="Screenshot 2025-10-18 232219" src="https://github.com/user-attachments/assets/6c84a22f-65ba-49a0-93e0-7a38ef1feb8f" />

## Result
The  Python program that calculates the **sum of all elements** in a list is executed succesfully.
# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without the letter 'e':", l1)


```
## Output
<img width="1027" height="292" alt="Screenshot 2025-10-18 232957" src="https://github.com/user-attachments/assets/312e827f-cfaa-40f3-9228-1f0b58460eef" />
# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(s):
    
    n = int(input("Enter the index of the character to remove: "))
    
    
    a = ""
    
    
    for i in range(len(s)):
        if i != n:
            a += s[i]
    
   
    return a
input_string = input("Enter a string: ")
result = remove(input_string)
print("String after removing character at specified index:", result)
```
## Output
<img width="1034" height="223" alt="Screenshot 2025-10-18 233448" src="https://github.com/user-attachments/assets/a7f4bf35-1976-4b8f-bce8-2589feaf77b4" />


## Result
The Python program that accepts a string and removes the character at a specified index is executed successfully.
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
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```

x = ('a', 'b', 'n', 3, 5, 8, 'z')


has_n = 'n' in x
has_8 = 8 in x


print("Does the tuple contain 'n'? :", has_n)
print("Does the tuple contain 8?   :", has_8)
```
## Output
<img width="1022" height="179" alt="Screenshot 2025-10-18 234023" src="https://github.com/user-attachments/assets/a46f3714-fbd4-46dd-9c79-5796df0b689b" />

## Result
The Python program that checks if the element `'n'` and the element `8` exist within a given tuple is ecxecuted successfully.
