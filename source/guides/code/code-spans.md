# Code Spans

Code spans represent fragments of code used within a normal paragraph.

In Markdown, a code span is defined by placing a fragment of code within
backtick characters. For example, the following places the word 'printf'
inside of a code span:

```markdown
Use the `printf` function to output text to the screen.
```

Unlike code blocks, if a code span covers multiple lines it is rendered as a
single line. For example:

```markdown
`int main()
{
  printf("Hello, world!\n");
}`
```
