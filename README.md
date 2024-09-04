# Duplicate-Number-From-List
Write a function to remove the duplicate numbers on given integer array/list.

Example

remove_duplicates([1, 1, 2, 2, 3, 4, 5])
Output : [1, 2, 3, 4, 5]

--> 2 Approaches
--> 1st Approach:
                USing list(set()) to convert in set() then convert back into list() so that duplicate elements will get removed.
                Time & Complexity --> O(n)

--> 2nd Approach:
                Using Empty list compare with present list elements ro insert those in empty list by comparing those.
                Time & Space Complexity --> O(n)
        
