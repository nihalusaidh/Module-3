# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
a=[1,2,3,4,5]
total=sum(a)
print(total)

## Output

<img width="1911" height="793" alt="m3 o1" src="https://github.com/user-attachments/assets/3db8a798-4484-44a6-ad11-a84b963d7738" />


## Result
Thus Python program that calculates the **sum of all elements** in a list is executed successfully.


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
import re
items =['goal','new','user','sit','eat','dinner']
new=[]
for item in items:
    if not re.search(r'e',item):
        new.append(item)
print(new)
## Output
<img width="1919" height="795" alt="m3 o2" src="https://github.com/user-attachments/assets/3734530d-c9eb-4e61-98b8-10003b2e74ea" />



## Result
Thus the Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is executed successfully.

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
def remove(s):
    n = int(input("Enter index to remove: "))
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a

string = input("Enter a string: ")
print("Modified string:", remove(string))

## Output
<img width="1913" height="796" alt="m3 o3" src="https://github.com/user-attachments/assets/3dc261b3-bb82-420d-b57f-72175940efc3" />


## Result
Thus Python program that accepts a string and removes the character at a specified index is executed successfully.

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
a="google"
b=a[::-1]
print(b)
if a==b:
    print("It is a palindrome")
else:
    print("Not a palindrome")


## Output
<img width="1911" height="789" alt="m3 o4" src="https://github.com/user-attachments/assets/e2209ebb-939e-467c-9d5a-145e3bc0f7b2" />


## Result
Thus Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions. 


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

x = ('a', 'b', 'n', 5, 8, 10)

check_n = 'n' in x

check_8 = 8 in x


print("'n' in tuple:", check_n)
print("8 in tuple:", check_8)
## Output
<img width="1919" height="788" alt="m3 o5" src="https://github.com/user-attachments/assets/f39aa4f4-e5cf-4a78-867a-288c9cf4383c" />


## Result 
Thus the Python program that checks if the element `'n'` and the element `8` exist within a given tuple is executed successfully.





