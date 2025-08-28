# week-2-python-assignment
 This assignment demonstrates Python list operations by creating an empty list named my_list and performing various manipulations. These include appending elements, inserting a value at a specific position, extending the list with additional values, removing the last element, sorting the list in ascending order, and finding the index of a specific value. It showcases practical use of Python’s built-in list methods to store, update, and organize data efficiently.
#Code
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend my_list with another list
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort the list in ascending order
my_list.sort()

# Find and print the index of value 30
print(my_list.index(30))

# Print the final list to see the result
print(my_list)

