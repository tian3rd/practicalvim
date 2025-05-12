# Practical Vim

> [!WARNING] Based on vim 7.4

## Tip76: () to capture child match

```text
I love Paris in the
the springtime.
```

```vim
/\v<(\w+)\_s+\1>
```
`\v` is for very magic mode
`\_s` matches any whitespace including newlines.
`\1` is a backreference to the first capture group.
`<>` marks the start and end of the capture group.


