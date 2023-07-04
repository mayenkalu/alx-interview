# Lockboxes

* Lockboxes are secure containers used to protect valuable items or sensitive information.
* They come in different sizes, materials, and security levels. Lockboxes have lock mechanisms, such as keys, combinations, or biometrics, to restrict access.
* They are used in various contexts, including homes, real estate, emergency access, key management, medication storage, and data protection.
* While lockboxes enhance security, they are not completely invulnerable.
* Choosing the right lockbox and following best practices is essential.

## Task Description

`canUnlockAll(boxes)` function determines whether it is possible to unlock all the boxes in a given list of lists.

Here's how the function works:

The function takes a parameter, `boxes`, which is a list of lists. Each sublist represents a box and contains the keys to other boxes.
The boxes are numbered sequentially from 0 to n - 1, where n is the total number of boxes.
The function assumes that the first box, `boxes[0]`, is initially unlocked.
A key with the same number as a box can open that box. For example, if box 2 contains a key with the number 2, it can open box 2.
The function traverses through the boxes and checks if there is a key for each box that has not been opened yet.
If a box can be opened, the function updates a set called `opened` to keep track of the boxes that have been opened.
The function continues this process until it has iterated through all the boxes and determined if they can all be opened.
Finally, the function returns `True` if all boxes can be `opened` (i.e., if the length of opened is equal to the total number of boxes), and `False` otherwise.
Here's the prototype of the function:

```python
def canUnlockAll(boxes):
    # Implementation logic goes here
    pass
```

Example Usage:

```python
boxes = [[1], [2], [3], []]
print(canUnlockAll(boxes))  # Output: True

boxes = [[1, 2], [3], [4], []]
print(canUnlockAll(boxes))  # Output: False
```

In the first example, there are four boxes, and each box contains the key to the next box. Therefore, all the boxes can be opened. In the second example, box 0 contains keys to boxes 1 and 2, but box 1 does not have a key to box 2. Thus, not all boxes can be opened, and the function returns `False`.
