# Python List Operations Example

This Python script demonstrates basic list operations step-by-step, including appending, inserting, extending, removing elements, sorting, and finding the index of an element.

---

## 📋 Steps Performed

1. **Create an Empty List**  
   Initializes an empty list named `my_list`.

2. **Append Values**  
   Adds `10`, `20`, `30`, and `40` to the list using the `.append()` method.

3. **Insert at a Specific Position**  
   Inserts the value `15` at index `1` (second position) using `.insert()`.

4. **Extend the List**  
   Adds multiple elements `[50, 60, 70]` at once using `.extend()`.

5. **Remove Last Element**  
   Removes the last element using `.pop()` without specifying an index.

6. **Sort the List**  
   Sorts all elements in ascending order using `.sort()`.

7. **Find Index of an Element**  
   Finds and prints the index position of the value `30` using `.index()`.

---

## 🖥️ Code

```python
# Step 1: Create an empty list
my_list = []

print("Initial List", my_list)

# Step 2: Append values
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

print("Appended values", my_list)

# Step 3: Insert 15 at index 1
my_list.insert(1, 15)
print("Inserting 15 at Index 1", my_list)

# Step 4: Extend with another list
my_list.extend([50, 60, 70])
print("Extended List:", my_list)

# Step 5: Remove last element
my_list.pop()
print("Remove last element", my_list)

# Step 6: Sort list in ascending order
my_list.sort()
print("List in ascending order", my_list)

# Step 7: Find and print index of 30
index_of_30 = my_list.index(30)
print("Final List:", my_list)
print("Index of 30:", index_of_30)
# Python List Operations Example

