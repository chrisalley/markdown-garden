# Indented Code Blocks

Indented code blocks are defined in Markdown by indenting each line of the
block by four spaces. For example, the following turns a code fragment written
in the C programming language into an indented code block:

```markdown
    #include <stdio.h>

    int main()
    {
      printf("Hello, world!\n");
    }
```

Indented code blocks can also be produced using tabs instead of spaces. One tab
is the equivalent of four spaces. For example:

```markdown
  #include <stdio.h>

  int main()
  {
    printf("Hello, world!\n");
  }
```

Indented code blocks continue until there is a line that is not indented (or it
is the end of the document).
