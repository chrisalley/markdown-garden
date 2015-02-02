# Inline Images

Inline images are defined in Markdown using similar syntax to [links](../links)
but by preceding the markup with an exclamation mark. Following the exclamation
mark, the image's alternative text is placed in square brackets followed by the
URL of the image in regular brackets. For example:

```markdown
![CommonMark logo](http://www.commonmark.org/logo.png)
```

An optional image title may be added after the URL, separated by a space and
surrounded by double quotes:

```markdown
![CommonMark logo](http://www.commonmark.org/logo.png "CommonMark logo")
```

If the destination URL is on the same server, you may use relative URLs like
this:

```markdown
![CommonMark logo](/logo.png)
```
