# vfastrht
vfastrht is a CC0 recursive hash table implementation.
## what is a recursive hash table?
a recursive hash table, or rht, is a hash table that creates a new level every time two entries conflict.\
it can extend indefinitely below; its access speed is O(logn). it is simpler than a traditional BST & it is faster than it when entry IDs have a roughly uniform distribution across the whole space under which IDs are valid on.\
it is very good when IDs are random (for example, hashes) or where each ID is just the increment of the previous & IDs are rarely removed (use a dynamic array in this case!).
