# task-1-main-flow-services-and-technologies
# Create a list
my_list = [1, 2, 3, 4, 5]
print("Initial list:", my_list)

# Add an element to the list
my_list.append(6)
print("After adding 6:", my_list)

# Remove an element from the list
my_list.remove(3)
print("After removing 3:", my_list)

# Modify an element in the list
my_list[0] = 10
print("After modifying first element to 10:", my_list)

# Create a dictionary
my_dict = {'name': 'Alice', 'age': 25}
print("\nInitial dictionary:", my_dict)

# Add a key-value pair to the dictionary
my_dict['city'] = 'New York'
print("After adding city:", my_dict)

# Remove a key-value pair from the dictionary
del my_dict['age']
print("After removing age:", my_dict)

# Modify a value in the dictionary
my_dict['name'] = 'Bob'
print("After modifying name to Bob:", my_dict)

# Create a set
my_set = {1, 2, 3}
print("\nInitial set:", my_set)

# Add an element to the set
my_set.add(4)
print("After adding 4:", my_set)

# Remove an element from the set
my_set.remove(2)
print("After removing 2:", my_set)

# Attempt to modify (add duplicate, which won't change the set)
my_set.add(3)  # This won't change the set as 3 is already present
print("After trying to add 3 again:", my_set)

# Print final states
print("\nFinal list:", my_list)
print("Final dictionary:", my_dict)
print("Final set:", my_set)

# OUTPUT
Initial list: [1, 2, 3, 4, 5]
After adding 6: [1, 2, 3, 4, 5, 6]
After removing 3: [1, 2, 4, 5, 6]
After modifying first element to 10: [10, 2, 4, 5, 6]

Initial dictionary: {'name': 'Alice', 'age': 25}
After adding city: {'name': 'Alice', 'age': 25, 'city': 'New York'}
After removing age: {'name': 'Alice', 'city': 'New York'}
After modifying name to Bob: {'name': 'Bob', 'city': 'New York'}

Initial set: {1, 2, 3}
After adding 4: {1, 2, 3, 4}
After removing 2: {1, 3, 4}
After trying to add 3 again: {1, 3, 4}

Final list: [10, 2, 4, 5, 6]
Final dictionary: {'name': 'Bob', 'city': 'New York'}
Final set: {1, 3, 4}

