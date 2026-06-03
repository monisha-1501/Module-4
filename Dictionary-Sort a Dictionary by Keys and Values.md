# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d = {'c': 3, 'a': 1, 'b': 2}

print("Original Dictionary:", d)

sorted_keys = dict(sorted(d.items()))
print("Sorted by Keys:", sorted_keys)

sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by Values:", sorted_values)
```

## Sample Output
<img width="1345" height="371" alt="{9C0F581C-0A96-41A9-B07C-A8F08FDC50E3}" src="https://github.com/user-attachments/assets/14ce45c3-cef7-427a-8a51-8eb3ba942423" />

## Result
The program successfully sorts the dictionary by keys and values and displays the results.
