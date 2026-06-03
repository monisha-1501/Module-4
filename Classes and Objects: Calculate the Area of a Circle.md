# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of Circle =", area)

r = float(input("Enter radius: "))

obj = cse()
obj.mech(r)
```

## Output
<img width="1261" height="361" alt="{8B383C5B-DA1E-4BC4-9DEE-F302CBDAAC0E}" src="https://github.com/user-attachments/assets/f8c6e09f-3f68-4fd0-957a-c56cd2227378" />

## Result
The program successfully calculates and prints the area of the circle for the given radius using a class method.
