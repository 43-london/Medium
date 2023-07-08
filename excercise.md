# Exercise

```python
Medium:

Exercise: ft_list_sort
Allowed functions: None

Create a function that sorts (in ascending order according to ASCII) the list that is passed to it. The sorting should be done by comparing the 'data' part of the nodes.

• The list will have a field 'next' and a field 'data'.
• The field 'data' is a pointer of type void, and you can assume that this pointer points to a string when sorting.
• The field ‘next’ is a pointer to the next node of the list or NULL if it is the last node.
• The function should change the 'next' links of a struct, not swap data of node i with data of node j.
• The function must take in two parameters: the address of a pointer to the first link and a pointer to the sorting function
• The function should be prototyped as:
void ft_list_sort(t_list **begin_list, int (*cmp)());

Note: cmp is a comparator function that returns a negative integer, zero, or a positive integer depending on whether the first argument is to be considered less than, equal to, or greater than the second.
```
# Submissions 
 git push your solution in this repo and hit /submit in Discord