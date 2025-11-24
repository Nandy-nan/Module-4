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
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius * radius
        print(f"The area of the circle with radius {radius} is {area:.2f}")

r = float(input("Enter the radius of the circle: "))

obj = cse()
obj.mech(r)

```



## Output
<img width="502" height="71" alt="image" src="https://github.com/user-attachments/assets/c7b6a5d1-4cad-44a6-b70b-fc5d72cea68d" />


## Result
The program executed successfully. It calculated the area of a circle using a class and method structure, and displayed the result based on user input.
