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

``` python
text = "google"

reverse = ""

for char in text:
    reverse = char + reverse

if text == reverse:
    print(text, "is a Palindrome")
else:
    print(text, "is not a Palindrome")
```

## Output
<img width="404" height="177" alt="image" src="https://github.com/user-attachments/assets/f94b8300-ebec-4989-b4ed-2e2a0cad518c" />

## Result
Thus, the Python program to check whether the string "google" is a palindrome without using built-in palindrome checking functions has been executed successfully.
