## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

def merge():
    result = {**dict1, **dict2}
    print(result)

merge()
```

## Output
<img width="1246" height="381" alt="{51551D81-793A-4B87-8143-A2E1FD47085E}" src="https://github.com/user-attachments/assets/facf8367-fbd1-4790-be23-9aa0e22ad58c" />

## Result
The program successfully merges two dictionaries using the ** unpacking operator and prints the merged dictionary.
