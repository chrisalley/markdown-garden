# Reference Images

Reference images are defined in Markdown by preceding the markup with an
exclamation mark followed by the image's alternative text in square brackets
followed by an image label in a second set of square brackets. At the end of
the document, the image label is placed in square brackets, followed by a
colon, followed by the destination URL. For example:

```markdown
![CommonMark logo][commonmark-logo]
```

    [commonmark-logo]: http://www.commonmark.org/logo.png

As with [inline images](../inline-images), reference images can contain an
optional title which is placed in double quotes following the image
destination URL:

```markdown
![CommonMark logo][commonmark-logo]
```

    [commonmark-logo]: http://www.commonmark.org/logo.png "CommonMark logo"

If the destination URL is on the same server, you may use relative URLs like
this:

```markdown
![CommonMark logo](commonmark-logo)
```

    [commonmark-logo]: /logo.png
