# Data_Structure_Python

1. Using float('inf') and float('-inf') (Most Common in CP)
    INF = float('inf')
    NEG_INF = float('-inf')


2. 

🔹 Example
d = {'a': 5, 'b': 9, 'c': 2}

print(max(d))                 # compares keys → 'c'
print(max(d, key=d.get))      # compares values → 'b'


Pythonic Shortcut
max_key = max(my_dict, key=my_dict.get)

key=my_dict.get tells max() to compare values instead of keys.

Equivalent to: max(my_dict, key=lambda k: my_dict[k])

Slightly slower (due to function calls), but very readable.
