Contains Duplicate in C++
Description

This program checks whether an array contains any duplicate elements.

It uses an unordered_set to store the numbers that have already been seen. If a number appears more than once, the program returns true. Otherwise, it returns false.

Features
Uses unordered_set for fast searching.
Checks for duplicate elements efficiently.
Returns true if a duplicate is found, otherwise returns false.

How It Works
Create an empty unordered_set.
Traverse each element of the array.
Check if the current element already exists in the set.
If it exists, return true.
Otherwise, insert the element into the set.
If no duplicates are found after checking all elements, return false.
