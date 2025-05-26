# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```
# Reg.No-212223060231
# Name-Royce Niran George A

class calc:
    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def add(self):
        return self.a + self.b

    def mul(self):
        return self.a * self.b

a = int(input())
b = int(input())
c = calc()
c.setvalues(a, b)

while True:
    choice = int(input("Enter 1 for Addition, 2 for Multiplication, 0 to Exit: "))
    
    if choice == 1:
        print("Result:", c.add())
    elif choice == 2:
        print("Result:", c.mul())
    elif choice == 0:
        print("Exiting!")
        break
    else:
        print("Invalid choice")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/97de141f-7d18-4478-b805-8ddea623c766)

### RESULT
Thus the program to perform addition and division operations using a class has been implemented and executed successfully.
