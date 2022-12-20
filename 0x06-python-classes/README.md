# 0x06. Python - Classes and Objects Projects

`0-square.py:` is a program that contains an empty class Square that defines a square.

`1-square.py:` is a program that contains a class Square that defines a square by: (based on `0-square.py`)

`2-square.py:` is a program that contains a class Square that defines a square by: (based on `1-square.py`)

`3-square.py:` is a program that contains a class Square that defines a square by: (based on `2-square.py`)

`4-square.py:` is a program that contains a class Square that defines a square by: (based on `3-square.py`)

`5-square.py:` is a program that contains a class Square that defines a square by: (based on `4-square.py`)

`6-square.py:` is a program that contains a class Square that defines a square by: (based on `5-square.py`)

`100-singly_linked_list.py:` is a program that contains a class Node that defines a node of a singly linked list by:

- Private instance attribute: data:
- property def data(self): to retrieve it
- property setter def data(self, value): to set it:
  data must be an integer, otherwise raise a TypeError exception with the message data must be an integer
- Private instance attribute: next_node:
- property def next_node(self): to retrieve it
- property setter def next_node(self, value): to set it:
  next_node can be None or must be a Node, otherwise raise a TypeError exception with the message next_node must be a Node object
- Instantiation with data and next_node: def **init**(self, data, next_node=None):
  Also:

The prgram contains a class SinglyLinkedList that defines a singly linked list by:

- Private instance attribute: head (no setter or getter)
- Simple instantiation: def **init**(self):
- Should be printable:
- print the entire list in stdout
  one node number by line
- Public instance method: def sorted_insert(self, value): that inserts a new Node into the correct sorted position in the list (increasing order)

`101-square.py:` is a program that contains a class Square that defines a square by: (based on 6-square.py)

- Private instance attribute: size:
- property def size(self): to retrieve it
- property setter def size(self, value): to set it:
  size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
- if size is less than 0, raise a ValueError exception with the message size must be >= 0
- Private instance attribute: position:
- property def position(self): to retrieve it
- property setter def position(self, value): to set it:
- position must be a tuple of 2 positive integers, otherwise raise a TypeError exception with the message position must be a tuple of 2 positive integer
  Instantiation with optional size and optional position: def **init**(self, size=0, position=(0, 0)):
- Public instance method: def area(self): that returns the current square area
- Public instance method: def my_print(self): that prints in stdout the square with the character #:
  if size is equal to 0, print an empty line
- position should be use by using space
- Printing a Square instance should have the same behavior as my_print()

`102-square.py:` is a program that contains a class Square that defines a square by: (based on 4-square.py)

- Private instance attribute: size:
- property def size(self): to retrieve it
- property setter def size(self, value): to set it:
  size must be a number (float or integer), otherwise raise a TypeError exception with the message size must be a number
  if size is less than 0, raise a ValueError exception with the message size must be >= 0
- Instantiation with size: def **init**(self, size=0):
- Public instance method: def area(self): that returns the current square area
- Square instance can answer to comparators: ==, !=, >, >=, < and <= based on the square area

`103-magic_class.py:` is a program that contains the Python class MagicClass that does exactly the same as a described Python bytecode.
