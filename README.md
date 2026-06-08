# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

      import math
      
      class cse:
          def mech(self, radius):
              area = math.pi * radius ** 2
              print(f"Area of circle: {area:.2f}")
      
      
      r = float(input())
      
      
      obj = cse()
      obj.mech(r)


## Output
<img width="955" height="240" alt="image" src="https://github.com/user-attachments/assets/437bc4e0-c2f2-4436-a879-f2b0a606dcc5" />

## Result
Thus the program executed successfully


## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

      dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
      dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
      merge (dict1,dict2): 
      res={**dict1 , **dict2} return 
      res 
      dict3=merge(dict1,dict2) 
      print(dict3)

## Output
<img width="805" height="165" alt="image" src="https://github.com/user-attachments/assets/ef5a960c-18c0-438c-b1ee-27dc6336326c" />

## Result
thus,the program has been executed successfully.

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

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
      try:
          # Taking 3 elements input from the user
          L = []
          for i in range(3):
              item = ['laptop','mobile','pen']
              L.append(item)
      
          # Trying to access index 4
          print(L[4])
      
      except IndexError:
          print("check index range")


## Output
<img width="957" height="246" alt="image" src="https://github.com/user-attachments/assets/21cae7ff-0700-4f76-8ed7-87549eac2381" />

## Result
Thus the program executed successfully
