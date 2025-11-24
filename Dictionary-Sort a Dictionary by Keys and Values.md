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
```
my_dict = {'banana': 3, 'apple': 1, 'orange': 2, 'mango': 4}
sorted_by_keys = dict(sorted(my_dict.items()))  # Sorting by keys (alphabetical)
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))  # Sorting by values (alphabetical)
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)


```


## Sample Output
<img width="757" height="119" alt="image" src="https://github.com/user-attachments/assets/9482d5d8-539c-4428-a5c6-91701c6f5909" />


## Result
The program executed successfully, and it correctly sorted the dictionary both by keys in alphabetical order and by values in numerical order. The original dictionary and the sorted versions were displayed as expected.

