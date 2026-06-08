# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
      data=eval(input())
      sort=dict(sorted(data.items()))
      print("Keys and Values sorted in alphabetical order by the key")
      for key, value in sort.items():
          print(f"({key}, {value}) ",end="")

## Sample Output
<img width="1190" height="110" alt="image" src="https://github.com/user-attachments/assets/906bf040-a55b-4524-8a10-ddfd7574df1f" />

## Result
Thus the program executed successfully
