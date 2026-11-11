
## What each file does

**Q1: Text Encryption**
Takes messages and processes them. It checks if a string can be a palindrome, cleans up spaces, reverses every second word, removes duplicates, and finds high-priority keywords like "Urgent" or "Security".

**Q2: Nested Tuples**
Practices indexing and slicing. It finds the deepest numbers (14 and 21) by counting brackets, then flattens the whole tuple into a 1D list using a stack (while loop). It also covers tuple packing and unpacking.

**Q3: Traffic Load**
Uses two formulas (discrete and continuous) to calculate projected traffic for three stores. Since we couldn't use the `math` library, I hardcoded the value of `e`. It also uses bitwise operators to simulate traffic surges and throttling.

**Q4: Shallow vs Deep Copy**
Shows how shallow copies share references (so changing the copy changes the original), while deep copies don't. Because the `copy` library wasn't allowed, I wrote a manual recursive function to do the deep copy.

**Q5: Set Operations**
Does basic set stuff like union, intersection, and difference. It also checks if identifiers exist, removes them using `discard()`, and filters the set to find even numbers above a certain threshold.

**Q6: Matrix Manipulation**
This one was tricky. It takes uneven matrices and adds zeros (padding) so they can actually be multiplied. Then it multiplies them using list comprehensions, swaps the outer rows and columns, and checks linear combinations.


## A note on libraries
No external libraries or advanced data structures were used. The only exception is `import random` in Q6, but that was specifically asked for in the question prompt (`random.randint`).
