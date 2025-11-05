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

```python
import re
i = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
a=r"^[^e]*$"
d=(n for n in i if re.match(a,n))
print(list(d))

```
## Output

<img width="429" height="262" alt="image" src="https://github.com/user-attachments/assets/390c95e8-1675-44be-892e-bc9ba14a51ff" />


## Result

The program successfully filters and returns all elements from the list that do not contain 'e',using regex
