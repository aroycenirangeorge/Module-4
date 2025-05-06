# Exp.No:20

## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM

To write a Python program to perform addition and division operations using a class named `Saveetha`.

---

### ALGORITHM

1. Begin the program.
2. Create a class `Saveetha`.
3. Define the following methods:

   * `__init__(self)` – initializes `a` and `b` to 0.
   * `setvalues(self, a, b)` – sets the values of `a` and `b`.
   * `add(self)` – returns the sum of `a` and `b`.
   * `div(self)` – returns the division of `a` by `b`, with a check for division by zero.
4. In the main block, get values for `a` and `b` from the user.
5. Display a menu to the user to perform operations repeatedly using a `while` loop.
6. Use appropriate conditionals to handle the choices.
7. Terminate the program when the user enters 0.

---

### PROGRAM

```python
# Reg.No: 212223060231
# Name: Royce Niran George A

class Saveetha:
    def __init__(self):
        self.a = 0
        self.b = 0

    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def add(self):
        return self.a + self.b

    def div(self):
        if self.b == 0:
            return "Division by zero is not allowed."
        return self.a / self.b

def main():
    obj = Saveetha()
    a = int(input("Enter value for a: "))
    b = int(input("Enter value for b: "))
    obj.setvalues(a, b)

    while True:
        print("\nMenu:")
        print("1. Addition")
        print("2. Division")
        print("0. Exit")
        choice = int(input("Enter your choice: "))

        if choice == 1:
            print("Addition Result:", obj.add())
        elif choice == 2:
            print("Division Result:", obj.div())
        elif choice == 0:
            print("Exiting!")
            break
        else:
            print("Invalid choice")

main()
```

---

### OUTPUT 

![image](https://github.com/user-attachments/assets/c0412731-647d-4b28-a447-34a2835ecc98)

---

### RESULT

Thus, the Python program for performing arithmetic calculations using a class was successfully executed and validated.

