# Exp.No: 19

## CLASS AND OBJECTS – AREA OF CIRCLE

---

### AIM

To write a Python program to take the radius from the user and find the area of a circle using the class name umbrella and function name rain.

---

### ALGORITHM

1. Begin the program.
2. Create a class named umbrella.
3. Define a method rain(self, r) that accepts a radius as input.
4. Use math.pi to calculate the area of the circle using the formula:
     Area = π × r²
5. Print the result with formatting.
6. Take input from the user for radius.
7. Create an object of the umbrella class and call the rain method.
8. End the program.

---

### PROGRAM

```python
#Reg.No: 212223060231
#Name: Royce Niran George A

import math

class umbrella:
    def rain(self, r):
        area = math.pi * r * r
        print(f"Area of the circle with radius {r} is: {area:.2f}")

# Input from user
radius = float(input("Enter the radius of the circle: "))

# Create object and call method
u = umbrella()
u.rain(radius)
```

---

### OUTPUT

```
Enter the radius of the circle: 4.5
Area of the circle with radius 4.5 is: 63.62
```

---

### RESULT

Thus, the program to compute the area of a circle using a class and object was written and executed successfully.
