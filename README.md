# Mini-project: List Sweep Algorithms 

This is a set of small exercises in writing algorithms that calculate 
something in a single *sweep* of a list, i.e., they are each based 
on a single loop that visits each list element once.  Thus each 
should operate in time linear in the length of the list, 
a.k.a. O(n) where n is the length of the list. 

## All same

A function that determines whether all the elements in a 
list are the same.   For example, all_same([1, 1, 1, 1]) == True, 
all_same([]) == True, all_same([1, 3, 1, 1]) == False. 

## Dedup

A function that returns a de-duplicated version of the input 
list.  Elements appear in the same order as the input list, 
but subsequences of equal elements are replaced by one 
representative.  For example, dedup([]) = [], dedup([1, 1, 2, 1, 1]) 
= [1, 2, 1]. 

## Max run 

A run is a subsequence with identifical values.  For example, in 
[1, 1, 2, 2, 3, 4, 4, 4, 2, 4, 4], the runs are [1, 1], [2, 2], [3],
[4, 4, 4], [2], and [4, 4].  The longest run is [4, 4, 4], which 
has 3 elements.  max_run([1, 1, 2, 2, 3, 4, 4, 4, 2, 4, 4]) should
return 3.  max_run([]) == 0, max_run([1, 2, 3]) = 1, and
max_run([1, 2, 1, 1]) = 2.  

I think none of these are really difficult, but they are approximately
in order of increasing difficulty. 

