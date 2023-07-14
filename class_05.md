# 401 class_05

## LINKED LISTS:

### What is a node?

- A node is an individual object that lives in a linked list that has data and an address assigned to it. Head and Current are reference nodes that tell you where the first and current nodes are.

### When should we use them?

- If you find yourself wanting to add a bunch of elements to a list and aren’t worried about finding elements again later (or you won’t need to traverse through the entirety of the list) a linked list could be your new best friend.

- If you ever have to do something that requires a lot of traversal, iteration, or quick index-level access, a linked list could be your worst enemy. An array might be a better solution, since you can find things quickly (a single chunk of allocated memory), and you can use an index to quickly retrieve a random element in the middle or end of the list without having to take the time to traverse through the whole entire thing.
