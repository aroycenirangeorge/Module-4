# Exp.No:17

## EXCEPTION HANDLING

---

### AIM

To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.
2. Read a string `input_str` from the user using `input()`.
3. Split the input string using commas (`,`) to create a list of grades.
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.
5. If the conversion is successful, print the list `l1` containing the integer values.
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.
7. Terminate the program.

---

### PROGRAM

```python
# Reg.No: 212223060231
# Name: Royce Niran George A

input_str = input("Enter grades separated by commas: ")
grades = input_str.split(',')

try:
    l1 = [int(grade.strip()) for grade in grades]
    print("The list of integer grades:", l1)
except ValueError:
    print("The grades you entered were in an invalid format.")
    print("Entered values:", grades)
```

---

### OUTPUT

![image](https://github.com/user-attachments/assets/2e4f2e3f-28ac-43bc-a405-e2f95442cff7)

---

### RESULT

Thus, the Python program for exception handling to validate grade inputs was successfully executed.
