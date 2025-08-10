task 1-
with open("sample.txt", "w") as f:
    f.write("Hello World!\n")
    f.write("Python File Handling Example.\n")
with open("sample.txt", "a") as f:
    f.write("This line is appended.\n")

with open("sample.txt", "r") as f:
    print("File Content:")
    print(f.read()
a = 10
b = 4

# Arithmetic
print("Addition:", a + b)
print("Subtraction:", a - b)

# Assignment
a += 5
print("After a += 5:", a)

# Bitwise
print("Bitwise AND:", a & b)
print("Bitwise OR:", a | b)
print("Bitwise XOR:", a ^ b)
print("Bitwise Left Shift:", a << 1)
print("Bitwise Right Shift:", a >> 1)

# Comparison
print("a > b:", a > b)

# Logical
print("Logical AND:", a > 5 and b < 10)

# ---------- 3. String Operations ----------
s = "  Python Programming Language  "
print("Original:", s)
print("Lowercase:", s.lower())
print("Uppercase:", s.upper())
print("Stripped:", s.strip())
print("Replace:", s.replace("Python", "Java"))
print("Split:", s.split())
print("Count of 'g':", s.count("g"))
print("Starts with '  Py':", s.startswith("  Py"))
print("Ends with 'age  ':", s.endswith("age  "))
print("Find 'Prog':", s.find("Prog"))
