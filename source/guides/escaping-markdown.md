# Escaping Markdown

Sometimes you may want to use a character that Markdown already uses for
formatting the document, such as an asterisk or exclamation mark. In these
cases, a backslash (`\`) can be used to "escape" from Markdown formatting being
applied using the character.

Any [ASCII][ascii] punctuation character can be escaped with a backslash. ASCII
characters are generally the characters found on a standard keyboard such as
`!`, `@`, and `*`. For example:

```markdown
This asterisk pair \*is escaped*\, but this pair *starts emphasising.*
```

If an non-ASCII character is used, such as a [Unicode](unicode) emoji, the
literal backslash will be rendered. For example:

```markdown
This backslash \😀 is rendered, as is the non-ASCII emoji.
```

Even though the backslash is an ASCII character, you are not required to escape
a backslash with another backslash for it to be rendered. For example:

```markdown
This backslash \ will be rendered as a literal backslash.
```

[ascii]: https://en.wikipedia.org/wiki/ASCII
[unicode]: https://en.wikipedia.org/wiki/Unicode
