# Fenced Code Blocks

Fenced code blocks are defined in Markdown by surrounding the code fragment
with a matching pair of at least three consecutive backtick characters or
tildes. For example, the following creates a code block with backticks:

    ```
    <script>
      alert('Hello, world!')
    </script>
    ```

And the following creates a code block with tidles:

    ~~~
    <script>
      alert('Hello, world!')
    </script>
    ~~~

A language may optionally be specified for the code block. The language is
specified after the opening backticks or tildes, for example:

    ```javascript
    <script>
      alert('Hello, world!')
    </script>
    ```

## Things to watch out for:

- Backticks and tildes cannot be mixed. A code block that opens with backticks
must also close with backticks. Similarly, a code block that opens with tildes
must conclude with tildes.
