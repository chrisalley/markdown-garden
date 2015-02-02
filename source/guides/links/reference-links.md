# Reference Links

Reference links are defined in Markdown by placing the link text in square
brackets followed by a link label in a second set of square brackets. At the
end of the document, the link label is placed in square brackets, followed by
a colon, followed by the destination URL. For example:

```markdown
[CommonMark website][commonmark]
```

    [commonmark]: http://www.commonmark.org


As with [inline links](../inline-links), reference links can contain an optional
title which is placed in double quotes following the link destination URL:

```markdown
[CommonMark website][commonmark]
```

    [commonmark]: http://www.commonmark.org "CommonMark"


If the destination URL is on the same server, you may use relative URLs like
this:

```markdown
[Spec page](spec)
```

    [spec]: /spec
