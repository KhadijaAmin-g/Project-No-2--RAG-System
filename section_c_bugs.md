# Section C Bugs

## Bug 1 -> we not return state in retrived_node
- Fix: Return `{"context": context}`


## Bug 2 -> chunk size is very small or threshold is also very strict
- Fix: Use a larger chunk size and lower the threshold or use normal similarity search with `k`.
