# Exp.No:18

## FILES - FREQUENCY OF CHARACTERS IN A FILE

---

### AIM

To write a Python program that reads a file and counts the frequency of each character in it.

---

### ALGORITHM

1. Begin the program.
2. Define the function `create_file()` that accepts two arguments:

   * `file_path`: The path to the file.
   * `content`: The string content to be written into the file.
3. Open the file specified by `file_path` in write mode (`'w'`), and write the provided `content` into the file.
4. Close the file (this is automatically done when exiting the `with` block).
5. Define the function `character_frequency()` that accepts one argument:

   * `file_path`: The path to the file whose character frequency is to be calculated.
6. Open the file specified by `file_path` in read mode (`'r'`), and read its content into the variable `content`.
7. Initialize an empty dictionary (`d1`) to store the frequency of each character using `defaultdict(int)`.
8. Loop through each character in the `content`:

   * For each character `ch`, increment its corresponding frequency in the dictionary `d1`.
9. Return the dictionary `d1`, which contains the frequency of each character in the file.
10. Terminate the program.

---

### PROGRAM

```python
# Reg.No: 212223060231
# Name: Royce Niran George A

from collections import defaultdict

def create_file(file_path, content):
    with open(file_path, 'w') as f:
        f.write(content)

def character_frequency(file_path):
    with open(file_path, 'r') as f:
        content = f.read()
    d1 = defaultdict(int)
    for ch in content:
        d1[ch] += 1
    return d1

# Main code
file_path = "sample.txt"
content = "Hello World! Welcome to the world of Python."
create_file(file_path, content)
result = character_frequency(file_path)

print("Character frequencies:")
for char, freq in result.items():
    print(f"'{char}': {freq}")
```

---

### OUTPUT

![image](https://github.com/user-attachments/assets/935c07d6-cc4d-43e8-bfe4-1ef508bd3417)

---

### RESULT

Thus, the program to find the frequency of each character in a file using Python was successfully executed.

