# Task sorting by priority is doing a very stupid thing.

- STATUS: OPEN
- PRIORITY: 80
- TAGS: scope

Grep refs.

What we are doing is essentially on each comparison during sorting converting 2 strings to 2 integers.
We need to cache the integers, but then we are introducing cache invalidation problems back.
