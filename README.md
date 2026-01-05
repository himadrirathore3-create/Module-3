# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
L=[153,147,124,102] 
 
print(sum(L)))
```
## Output
![Screenshot 2025-05-03 141049](https://github.com/user-attachments/assets/4eee36e8-2937-480e-b569-61ea8a518cb1)
## Result
Thus, the program has been successfully executed. 

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
l1=[] 

items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items: 

   if not re.search(r"e",i): 
      l1.append(i) 

print(l1)
```
## Output
![Screenshot 2025-05-03 141328](https://github.com/user-attachments/assets/1364682d-b510-462e-83ac-b9b874bfb755)
## Result
Thus, the program has been successfully executed. 

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(a,n):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
a=input()
n=int(input())
remove(a,n)

```
## Output
![Screenshot 2025-05-03 141551](https://github.com/user-attachments/assets/b090edbc-4c5f-4910-9df3-736ce9a3cebd)

## Result
Thus the program has been successfully executed



