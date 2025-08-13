# Python List Operations 🐍

This project demonstrates basic **list manipulation** in Python, including:
- Appending elements
- Inserting at a specific position
- Extending a list
- Removing elements
- Sorting
- Finding the index of a specific value

---

## Steps Performed

1. Create an empty list called `my_list`.
2. Append the values `10`, `20`, `30`, and `40` to the list.
3. Insert `15` at the **second position**.
4. Extend the list with another list: `[50, 60, 70]`.
5. Remove the **last element** from the list.
6. Sort the list in ascending order.
7. Find and print the **index** of the value `30`.

---

## Code Example

```python
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert at index 1
my_list.insert(1, 15)

# Extend with another list
my_list.extend([50, 60, 70])

# Remove last element
my_list.pop()

# Sort the list
my_list.sort()

# Find index of 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
print("Final List:", my_list)
