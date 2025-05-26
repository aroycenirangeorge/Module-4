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

```
# Reg.No-212223060231
# Name-Royce Niran George A

import sys
dic1 = {"A": 1, "B": 2, "C": 3}
dic2 = {"saveetha": "Raju", "sec": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}

print("Size of dic1:", str(sys.getsizeof(dic1)) + " bytes")
print("Size of dic2:", str(sys.getsizeof(dic2)) + " bytes")
print("Size of dic3:", str(sys.getsizeof(dic3)) + " bytes")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/7dba72f6-4a55-42eb-9ae2-4e587db2c358)


### RESULT
Thus the program to print the size of a dictionary using getsizeof() from the sys module has been implemented and executed successfully.
