# Record/replay testing

- STATUS: OPEN
- PRIORITY: 100
- TAGS: scope

Basically a test case should be a simple script that runs `tatr` commands. We record the state of a sandbox folder after the script and then replay the script and check if the state is expected.

The only problem I see is the Task IDs are based on time. We need to record the outcomes so it because irrelevant somehow.
