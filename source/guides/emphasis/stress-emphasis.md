# Stress Emphasis

Stress Emphasis is used to represent text that should be emphasised.

In Markdown, stress emphasis is defined by placing asterisks or underscores
around the text that is to be emphasised. For example, to emphasise the word
"quick":

```markdown
The *quick* brown fox jumped over the lazy dog.
```

```markdown
The _quick_ brown fox jumped over the lazy dog.
```

Using asterisks or underscores has the same result in most cases. However,
CommonMark compliant applications make a distinction when underscores are used
within words.

Asterisks may be used to emphasise text within a word, for example:

```markdown
The quick brown fox *jump*ed over the lazy dog.
```

The text "jump" is emphasised here. Whereas if an underscore is used, the word
"jump" is not emphasised; literal underscores are rendered instead:

```markdown
The quick brown fox _jump_ed over the lazy dog.
```

This is useful when using programming code and web addresses within Markdown
documents as these often contain underscores in the middle of words.

By default, applications and websites usually display stress emphasis as
italicised text.
