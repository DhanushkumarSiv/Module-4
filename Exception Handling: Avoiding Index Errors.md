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

```
list1 = [10, 20, 30, 40]
try:
    print(list1[5])  
except:
    print("You're out of list range")
```

## Output


![Screenshot 2025-05-23 205808](https://github.com/user-attachments/assets/735961b4-9634-438f-9f0b-1e645481a97a)


## Result

Therefore,the given python program is successfully verified
