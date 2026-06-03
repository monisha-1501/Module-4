# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
lines = [
    "This is a test",
    "Hello",
    "Today is sunny",
    "Python is fun"
]

count = 0

for line in lines:
    if line[0] != 'T':
        count += 1

print(count)
```

## Output
<img width="1291" height="469" alt="{D84FF4F7-CAFD-495F-B7D0-0B4C89F8A6AD}" src="https://github.com/user-attachments/assets/d9b48781-31d0-48f9-a9bb-60983c0b907e" />

## Result
The program counts and displays the number of lines that do not start with the letter 'T'.
