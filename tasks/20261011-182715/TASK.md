# The update language

- STATUS: OPEN
- PRIORITY: 100
- TAGS: scope

Instead of the zoo of commands like `tatr-untag`, `tatr-tag`, just have the Update Language which supports things like `-scope,+bug,close`. Comma separated list of actions to perform on the task.

---

Some design ideas:

```c
$ tatr ls -update -scope,close :scope and :bug
$ tatr update -untag scope -close :scope and :bug
```
