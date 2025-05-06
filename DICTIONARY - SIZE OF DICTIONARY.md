# Exp.No:16

## DICTIONARY - SIZE OF DICTIONARY

---

### AIM

To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.
2. Import the `sys` module to use the `getsizeof()` function.
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.
5. Print the size of each dictionary in bytes.
6. Terminate the program.

---

### PROGRAM

```python
#Reg.No: 212223060231
#Name: Royce Niran George A

import sys

# Step 1: Define sample dictionaries
dic1 = {1: 'a', 2: 'b'}
dic2 = {'name': 'Royce', 'dept': 'ECE', 'year': 2}
dic3 = {i: i*i for i in range(10)}

# Step 2: Get size of each dictionary
print("Size of dic1:", sys.getsizeof(dic1), "bytes")
print("Size of dic2:", sys.getsizeof(dic2), "bytes")
print("Size of dic3:", sys.getsizeof(dic3), "bytes")
```

---

### OUTPUT

![image](https://github.com/user-attachments/assets/84c13315-8fc7-402a-ba32-d68d37089c7d)


---

### RESULT

Thus, the program to calculate and print the size of dictionaries using `getsizeof()` was successfully executed.

