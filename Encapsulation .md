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
```python
class R:
    def __init__(self, l, w):
        self.__l = l
        self.__w = w
    def display(self):
        print(self.__l)
        print(self.__w)
rect = R(5,3)
rect.display()
```

## Output
![image](https://github.com/user-attachments/assets/f704de9f-55fc-4359-b981-6cc936e69f46)


## Result
Thus ,the program executed successfully.
