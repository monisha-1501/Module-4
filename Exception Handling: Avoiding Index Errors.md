# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="1263" height="302" alt="{12B83ACA-91B4-473A-BE9B-53C078F4850D}" src="https://github.com/user-attachments/assets/d82cd824-33ae-4497-a93d-dae1c692eaed" />

## Result
The program successfully handles the out-of-range index error using a try-except block and displays a custom error message.
