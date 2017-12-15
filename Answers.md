## Questions
1. What are the order of insertions/removals for the following data structures?
   - **Stack** - First In Last Out (FILO)
   - **Queue** - First In First Out (FIFO)
2. What is the retreival time complexity for the following data structures?
   - **Linked List** - Depending on the operation in the linked list, the time complexity is either O(1) or O(n). For example, inserting an element in the middle is O(1) if the reference to that node is already stored. If it's not and needs to be retrieved, the time complexity of the operation is then O(n).
   - **Hash Table** - Unless the operation requires you to resize the hash table to implement it, the time complexity is O(1). If you do need to resize the hash table, that specific operation is O(n). The vast majority of operations for hash tables are O(1).
   - **Binary Search Trees** - The time complexity of binary search trees is typically O(log n), but that's only true if the tree is balanced one. If the tree is unbalanced, it could shift the time complexity to O(n) since an unbalanced tree negates the halving effect of binary search trees.
2. What are some advantages to using a Hash Tables over an array in JavaScript?
    - Hash tables are a better way to store pairs of information, since they work with keys and values.
    - Hash tables are faster, since arrays' functions are largely leveraged through iteration. A hash table differs in that the operation is immediate. 
