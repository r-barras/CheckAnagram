# CheckAnagram
A simple string comparator that checks if two strings of equal lengths share the exact same words using ASCII

Given the task of determining if two words of equal lengths share the same letters I considered different approaches:
- To iterate through one of the letters and pop() the corresponding letter in the other word; then checking if the second word has any letters left;
- To iterate (...) and check if every letter is "in" the second word (shortcomings if there are duplicates, possibly)

Finally I understood that using ASCII could be a better solution and wrote this simple program to make use of it
