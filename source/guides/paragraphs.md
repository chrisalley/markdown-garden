# Paragraphs

Paragraphs are self contained units of writing that focus on a particular point
or idea.

In Markdown, paragraphs can be typed in plain text, without indentation or
special formatting characters. For example, in Markdown, the following is a
paragraph:

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam eget eros in nulla dignissim suscipit. Phasellus tempor nisl sed nulla eleifend, ac imperdiet ipsum aliquam. In ac eros ac ligula varius tempor. Phasellus efficitur volutpat ipsum, auctor faucibus velit finibus non. Fusce a nisl vitae diam faucibus vestibulum. Praesent velit massa, laoreet a rhoncus non, luctus in ligula.
```

Paragraphs may also be split over multiple lines for readability when writing
the document. For example:

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Nullam eget eros in nulla dignissim suscipit. Phasellus
tempor nisl sed nulla eleifend, ac imperdiet ipsum
aliquam. In ac eros ac ligula varius tempor. Phasellus
efficitur volutpat ipsum, auctor faucibus velit finibus
non. Fusce a nisl vitae diam faucibus vestibulum.
Praesent velit massa, laoreet a rhoncus non, luctus in
ligula.
```

Applications will join the individual lines together to form a single
paragraph, so it will be rendered the same as in the first example.

To create a new paragraph, separate two blocks of text with a blank line.
For example:

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam eget eros in nulla dignissim suscipit. Phasellus tempor nisl sed nulla eleifend, ac imperdiet ipsum aliquam. In ac eros ac ligula varius tempor. Phasellus efficitur volutpat ipsum, auctor faucibus velit finibus non. Fusce a nisl vitae diam faucibus vestibulum. Praesent velit massa, laoreet a rhoncus non, luctus in ligula.

Vivamus nec volutpat neque. Nam pulvinar vehicula magna, non sagittis augue molestie eget. Vestibulum eget blandit erat, ut malesuada nisl. Duis in pretium ipsum, vitae tempor dolor. Nulla rutrum gravida mi, ac pellentesque nulla maximus in. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nulla sed quam erat. Nulla quis ullamcorper turpis. Pellentesque feugiat, est in fermentum iaculis, massa tortor tempor massa, a laoreet justo lorem vel quam.
```

## Things to watch out for:

- Indentation does not define a new paragraph in Markdown. Indenting a line of
text two to three spaces will be ignored and indenting it four spaces will turn
it into a code block.
- A new line does not represent a new paragraph. By default, Markdown parsers
will join two lines together to form a single paragraph. However, some
applications may render the two lines as actual lines (but still part of the
same paragraph).
