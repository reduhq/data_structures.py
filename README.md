
# CONTENT
- [DATA STRUCTURES](#data-structures)
	- Lists
	- Tuples
	- Dictionaries
	- Sets
- [METHODS](#methods)
	- [String Methods](#string-methods)
	- [List Methods](#list-methods)
	- [Dictionary Methods](#dict-methods)
	- [Set Methods](#set-methods)

# DATA STRUCTURES 

1. Lists:
   - Ordered sequence of elements.
   - Mutable: You can add, remove, or modify elements.
   - Defined using square brackets [ ].
   - Allows duplicates.

2. Tuples:
   - Ordered sequence of elements.
   - Immutable: Once created, they cannot be modified.
   - Defined using parentheses ( ).
   - Allows duplicates.

3. Dictionaries:
   - Associative data structure that stores key-value pairs.
   - Mutable: You can add, remove, or modify elements.
   - Defined using curly braces { }.
   - Does not allow duplicate keys, but values can be repeated.

4. Sets:
   - Unordered collection of unique elements.
   - Mutable: You can add or remove elements.
   - Defined using curly braces { } or the set() function.
   - Does not allow duplicate elements.

# METHODS 

## STRING METHODS
>NOTE: To see more list methods, visit [Python String Methods](https://www.w3schools.com/python/python_ref_string.asp)

|Method| Description | example
| ------------------ |:-------------: |:-------------:|
[DIR](https://www.w3schools.com/python/ref_func_dir.asp) | The `dir()` method returns the list of valid attributes of the passed object | dir(object)
[UPPER](https://www.w3schools.com/python/ref_string_upper.asp) | The `upper()` method returns a string where all characters are in upper case | my_string.upper()
[LOWER](https://www.w3schools.com/python/ref_string_lower.asp) | The `lower()` method returns a string where all characters are lower case | my_string.lower()
[CAPITALIZE](https://www.w3schools.com/python/ref_string_capitalize.asp) | The `capitalize()` method returns a string where the first character is upper case, and the rest is lower case | my_string.capitalize()
[FIND](https://www.w3schools.com/python/ref_string_find.asp) | The `find()` method finds the first occurence of the specified value. The find() method returns -1 if the value is not found. | my_string.find("welcome")
[INDEX](https://www.w3schools.com/python/ref_string_index.asp) | The `index()` method finds the first occurence of the specified value. The index() method rises an exception if the value is not found | my_string.("hello")
[ISNUMERIC](https://www.w3schools.com/python/ref_string_isnumeric.asp) | The `isnumeric()` method returns True if all the characters are numeric (0-9), otherwise False | my_string.isnumeric()
[ISALPHA](https://www.w3schools.com/python/ref_string_isalpha.asp) | The `isalpha()` method returns True if all the characters are alphabeth letters (a-z). Example of characters that are not alphabet letters: (space)!#%&? etc. | my_string.isalpha()
[COUNT](https://www.w3schools.com/python/ref_string_count.asp) | The `count()` method returns the number of times a specified value appears in the string | my_string.count("apple")
[LEN](https://www.w3schools.com/python/ref_func_len.asp) | `len()` is a function that returns an integer which is the length of the string | len(my_string)
[STARTSWITH](https://www.w3schools.com/python/ref_string_startswith.asp) | The `startswith()` method returns True if the string starts with the specified value, otherwise False | my_string.startswith("Hi")
[ENDSWITH](https://www.w3schools.com/python/ref_string_endswith.asp) | The `endswith()` method returns True if the string ends with the specified value, otherwise False | my_string.endswith(".")
[REPLACE](https://www.w3schools.com/python/ref_string_replace.asp) | The `replace()` method replaces a specified phrase with another specified phrase | my_string.replace("bananas", "apples")
[SPLIT](https://www.w3schools.com/python/ref_string_split.asp) | The `split()` method splits a string into a list | my_string.split(", ")	

## LIST METHODS
```python
# LIST Creates a list
list(["hello", True, 25])
my_list = ["hello", True, 25]
```
>NOTE: To see more list methods, visit [Python List Methods](https://www.w3schools.com/python/python_lists_methods.asp)

|Method| Description | example
| ------------------ |:-------------: |:-------------:|
[LEN](https://www.w3schools.com/python/ref_func_len.asp) | The `len()` function returns the number of items in a list | len(my_list)
[APPEND](https://www.w3schools.com/python/ref_list_append.asp) | The `append()` method appends an element to the end of the list | my_list.append("hahaha")
[INSERT](https://www.w3schools.com/python/ref_list_insert.asp) | The `insert()` method inserts the specified value at the specified position | my_list.insert(2, "apple")
[EXTEND](https://www.w3schools.com/python/ref_list_extend.asp) | the `extend()` method adds the specified list elements (or any iterable) to the end of the current list | my_list.extend([False, 20])
[POP](https://www.w3schools.com/python/ref_list_pop.asp) | The `pop()` method removes the element at the specified position | my_list.pop(0)
[REMOVE](https://www.w3schools.com/python/ref_list_remove.asp) | The `remove()` method removes the specified item | my_list.remove("apple")
[CLEAR](https://www.w3schools.com/python/ref_list_clear.asp) | The `clear()` method removes all the elements from a list | my_list.clear()
[SORT](https://www.w3schools.com/python/ref_list_sort.asp) | The `sort()` method sorts the list ascending by default | my_list.sort(), my_list.sort(reverse=True)
[REVERSE](https://www.w3schools.com/python/ref_list_reverse.asp) | The `reverse()` method reverses the sorting order of the elements | my_list.reverse()

## DICT METHODS
```python
# DICT Creates a dictionary
dict(name="Liam", age=25, city="Madrid")
my_dict = {
	"name": "Liam",
	"age": 25,
	"city": "Madrid"
}
```
>NOTE: To see more dict methods, visit [Python Dictionary Methods](https://www.w3schools.com/python/python_ref_dictionary.asp)

|Method| Description | example
| ------------------ |:-------------: |:-------------:|
[KEYS](https://www.w3schools.com/python/ref_dictionary_keys.asp) | The `keys()` method returns a view object. The view object contains the keys of the dictionary, as a list. | my_dict.keys()
[GET](https://www.w3schools.com/python/ref_dictionary_get.asp) | The `get()` method returns the value of the item with the specified key, if the key doesn't exist, returns None | my_dict.get("name")
[CLEAR](https://www.w3schools.com/python/ref_dictionary_clear.asp) | The `clear()` method removes all items from the dictionary | my_dict.clear()
[POP](https://www.w3schools.com/python/ref_dictionary_pop.asp) | The `pop()` method removes the specified item from the dictionary | my_dict.pop("name")
[ITEMS](https://www.w3schools.com/python/ref_dictionary_items.asp) | the `items()` method is used to return the list with all dictionary keys with values | my_dict.items()

## SET METHODS
```python
# SET creates a set
set(["Luis", "Jilliam"])
my_set = {"Luis", "Jilliam"}

# Creating an inmutable set
frozenset(["Luis", "Jilliam"])
```
>NOTE: To see more set methods, visit [Python Set Methods](https://www.w3schools.com/python/python_ref_set.asp)

|Method| Description | example
| ------------------ |:-------------: |:-------------:|
[ISSUBSET](https://www.w3schools.com/python/ref_set_issubset.asp) | Return True if all items in set x are present in set y | my_set_x.issubset(my_set_y)
[ISSUPERSET](https://www.w3schools.com/python/ref_set_issuperset.asp) | Return True if all items set y are present in set x | my_set_x.issuperset(my_set_y)
[ISDISJOINT](https://www.w3schools.com/python/ref_set_isdisjoint.asp) | Return True if no items in set x is present in set y | my_set_x.isdisjoint(my_set_y)
