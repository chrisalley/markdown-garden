# CommonMark

A strongly specified, highly compatible implementation of Markdown.

## What is Markdown?

Markdown is a plain text format for writing structured documents, based on conventions used for indicating formatting in email and usenet posts. It was developed in 2004 by [John Gruber](https://en.wikipedia.org/wiki/John_Gruber), who wrote the first markdown-to-html converter in Perl, and it soon became widely used in websites. By 2014 there were dozens of implementations in many languages.

## Why is a spec needed?

John Gruber’s [canonical description of Markdown’s syntax](http://daringfireball.net/projects/markdown/syntax) does not specify the syntax unambiguously.

In the absence of a spec, early implementers consulted the original `Markdown.pl` code to resolve these ambiguities. But `Markdown.pl` was quite buggy, and gave manifestly bad results in many cases, so it was not a satisfactory replacement for a spec.

Because there is no unambiguous spec, implementations have diverged considerably. As a result, users are often surprised to find that a document that renders one way on one system (say, a GitHub wiki) renders differently on another (say, converting to docbook using Pandoc). To make matters worse, because nothing in Markdown counts as a “syntax error,” the divergence often isn't discovered right away.

There's no standard test suite for Markdown; [the unofficial MDTest](https://github.com/michelf/mdtest/) is the closest thing we have. The only way to resolve Markdown ambiguities and inconsistencies is [Babelmark](http://johnmacfarlane.net/babelmark2/), which compares the output of 20+ implementations of Markdown against each other to see if a consensus emerges.

We propose a **standard, unambiguous syntax specification for Markdown**, along with a **suite of comprehensive tests** to validate Markdown implementations against this specification. We believe this is necessary, even essential, for the future of Markdown.

That's what we call **CommonMark**.  Markdown Logo

## Who are you?

We're a group of Markdown fans who either work at companies with industrial scale deployments of Markdown, have written Markdown parsers, have extensive experience supporting Markdown with end users – or all of the above.

- **John MacFarlane**, jgm@berkeley.edu
- **David Greenspan**, david@meteor.com
- **Vicent Marti**, vicent@github.com
- **Neil Williams**, neil@reddit.com
- **Benjamin Dumke-von der Ehe**, ben@stackexchange.com
- **Jeff Atwood**, jatwood@codinghorror.com

## How can I help?

Read the spec, run the test suite, and exercise our [reference implementations](http://code.commonmark.org/). Provide feedback.

Perhaps the best way to provide feedback is to **implement your own CommonMark parser**, as one of our major goals is to strongly specify Markdown, and to eliminate the many old inconsistencies and ambiguities that made using Markdown so difficult. Did we succeed?

## Where can I find it?

We'll operate commonmark.org indefinitely as a central hub, with the following essential resources:

### [spec.commonmark.org](http://spec.commonmark.org)

The official specification for CommonMark.

### [code.commonmark.org](http://code.commonmark.org)

The official reference implementation and validation test suite on GitHub.

### [talk.commonmark.org](http://talk.commonmark.org)

The official Discourse discussion area and mailing list.

### [try.commonmark.org](http://try.commonmark.org)

The official dingus which allows people to experiment.

## When is the spec final?

The current version of the CommonMark spec is complete (two years in the making!), but provisional pending public feedback, testing, and evaluation.

With your help, we plan to announce a finalized 1.0 spec and test suite in the next few months, along with implementations in many different languages.
