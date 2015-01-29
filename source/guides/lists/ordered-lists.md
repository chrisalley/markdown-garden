# Ordered Lists

Ordered lists represent lists of items, where the order of the items is
important. If an ordered list is reordered, the semantic meaning of the
document will change.

In Markdown, an ordered list is defined by placing a decimal number (0-9)
followed by a dot or a decimal number followed up a closing bracket, followed
by a space, at the start of each list item. For example:

```markdown
1. Aristotle
2. Kant
3. Russell
```

```markdown
1) Aristotle
2) Kant
3) Russell
```

A new ordered list can be started by changing the list marker:

```markdown
1. Item in first list
2. Another item in first list
1) Item in second list
2) Another item in second list
```

The order of the numbers does not matter. For example, the following produces a
single ordered list:

```markdown
1. Aristotle
1. Kant
1. Russell
```
