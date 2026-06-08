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
