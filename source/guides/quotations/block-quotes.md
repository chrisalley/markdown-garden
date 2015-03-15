# Block Quotes

Block quotes represent one or more lines of text (or other content) that have
been quoted from another source.

In Markdown, a block quote is defined by placing a greater-than sign,
optionally followed by a space, at the start of each paragraph of the block
quote. For example:

```markdown
> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam eget eros in nulla dignissim suscipit. Phasellus tempor nisl sed nulla eleifend, ac imperdiet ipsum aliquam.
```

Block quotes may also be split over multiple lines for readability by placing
a greater-than sign at the start of each line. For example:

```markdown
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
> Nullam eget eros in nulla dignissim suscipit. Phasellus
> tempor nisl sed nulla eleifend, ac imperdiet ipsum
> aliquam.
```

If multiple paragraphs in block quotes are placed directly next to one another
they will be joined together to produce a single block quote:

```markdown
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
> Nullam eget eros in nulla dignissim suscipit. Phasellus
> tempor nisl sed nulla eleifend, ac imperdiet ipsum
> aliquam.

> In ac eros ac ligula varius tempor. Phasellus
> efficitur volutpat ipsum, auctor faucibus velit finibus
> non. Fusce a nisl vitae diam faucibus vestibulum.
> Praesent velit massa, laoreet a rhoncus non, luctus in
> ligula.
```

Block quotes may also contain other Markdown elements nested inside of
them, for example headers and lists:

```markdown
> This is a block quote containing a header
>
> # This is a header
>
> And a list
>
> 1. Item One
> 2. Item Two
```
