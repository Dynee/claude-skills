Save the full conversation from this session to a file.

Determine the output path:
- If $ARGUMENTS ends in `.md`, use `~/Projects/AIChats/$ARGUMENTS`
- Otherwise use `~/Projects/AIChats/$ARGUMENTS.md`

Reconstruct the entire conversation from your context, from the very first message to the most recent. Write it to the output path using the Write tool, formatted as markdown:

```
# <chat name derived from $ARGUMENTS>

**User:** <message>

**Assistant:** <message>

...
```

Preserve code blocks with their language annotations. Do not summarize or omit any messages — include everything.
