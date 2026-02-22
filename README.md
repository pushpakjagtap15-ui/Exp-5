# # Experiment 5: Implementation of Set and Dictionary in Python

## Title
Implementation of Set and Dictionary in Python

---

## Aim
To study and implement set data structure in Python and perform various set and dictionary operations.

---

## Objectives
- Understand the concept of sets  
- Perform set creation and basic operations  
- Apply mathematical set operations  
- Understand dictionary structure  
- Perform insertion, deletion, and access of data  
- Apply dictionary methods  

---

## Theory: Sets
A **set** in Python is an unordered collection of unique elements. Sets are defined using curly braces `{}` or the `set()` constructor.

### Characteristics of Set
- **Unordered:** Elements do not have a defined sequence or index  
- **No duplicate elements:** Only unique items are stored  
- **Mutable:** The set can be modified after creation  
- **No Indexing:** Sets do not support access via index positions  

### Mathematical Set Operations
- **Union (`|`)**: Combines elements from both sets  
- **Intersection (`&`)**: Identifies elements common to both sets  
- **Difference (`-`)**: Identifies elements in the first set but not the second  
- **Symmetric Difference (`^`)**: Identifies elements in either set, but not both  

---

## Theory: Dictionary
A **dictionary** is an unordered collection of key-value pairs. Each key must be unique, while values may be duplicated.

### Characteristics of Dictionary
- **Key-value based:** Data is stored and accessed via unique keys  
- **Mutable:** The dictionary structure can be modified after creation  
- **Unique Keys:** Each key acts as a unique identifier  
- **Modifiable Values:** Values associated with keys can be updated or changed  

### Syntax
```python
dictionary = {key: value}
Dictionaries are widely used in real-life applications such as student records, phone books, and configuration data.

Practical Implementation
Set Operations
python
# Set creation
set1 = {1, 2, 3, 4}
set2 = {3, 4, 5, 6}

# Union
print(set1 | set2)   # {1, 2, 3, 4, 5, 6}

# Intersection
print(set1 & set2)   # {3, 4}

# Difference
print(set1 - set2)   # {1, 2}

# Symmetric Difference
print(set1 ^ set2)   # {1, 2, 5, 6}
Dictionary Operations
python
# Dictionary creation
student = {"Name": "Pushpak", "PRN": 25070123148, "Branch": "E&TC"}

# Access
print(student["Name"])   # Pushpak

# Insertion
student["Marks"] = 85

# Deletion
del student["Branch"]

# Update
student["Marks"] = 90

# Methods
print(student.keys())    # dict_keys(['Name', 'PRN', 'Marks'])
print(student.values())  # dict_values(['Pushpak', 25070123148, 90])
Applications of Set
Removing duplicate records

Membership testing

Mathematical computations

Applications of Dictionary
Student information systems

Phone directories

Database records

Configuration files

Conclusion
Sets efficiently handle unique data and support mathematical operations, making them useful for data processing tasks.
Dictionaries provide efficient storage and retrieval of data using keys, making them essential for real-world applications.

