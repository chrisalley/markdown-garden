# Strong Importance

Strong importance is used to represent text that should be given extra emphasis.

In Markdown, stress emphasis is defined by placing double asterisks or
underscores around the text that is to be emphasised. For example, to give
strong importance to the word "lazy":

```markdown
The quick brown fox jumped over the **lazy** dog.
```

```markdown
The quick brown fox jumped over the __lazy__ dog.
```

Using asterisks or underscores has the same result in most cases. However, as
with [stress emphasis](../stress-emphasis), CommonMark compliant applications
make a distinction when underscores are used within words.

Asterisks may be used to give strong importance within a word, for example:

```markdown
The quick brown fox **jump**ed over the lazy dog.
```

The text "jump" is given strong importance here. Whereas if double underscores
are used, the word "jump" is not given strong importance; literal underscores
are rendered instead:

```markdown
The quick brown fox __jump__ed over the lazy dog.
```

This is useful when using programming code and web addresses within Markdown
documents as these often contain underscores in the middle of words.

By default, applications and websites usually display strong importance as
bold text.
