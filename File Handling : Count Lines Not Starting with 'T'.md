# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
try:
    with open('story.txt', 'r') as file:
        count = 0  

        for line in file:
            if not line.startswith('T'): 
                count += 1 
    print(f"The number of lines not starting with 'T': {count}")

except FileNotFoundError:
    print("The file 'story.txt' was not found.")


```

## Output
<img width="445" height="216" alt="image" src="https://github.com/user-attachments/assets/134aee2f-89dc-45dd-b0ee-5f3b5437fffe" />


## Result
The program successfully reads the file story.txt, counts the lines that do not start with the letter 'T', and prints the result. If the file is not found, it gracefully handles the error and displays a message.
