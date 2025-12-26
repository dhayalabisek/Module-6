# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, l, b):
        self.__length = l
        self.__breadth = b
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)
r = Rectangle(10, 5)
```
## Output
<img width="1694" height="727" alt="image" src="https://github.com/user-attachments/assets/206d00ab-6335-4d41-a740-0c489b29c0ad" />

## Result
Hence the program is written and executed successfully
