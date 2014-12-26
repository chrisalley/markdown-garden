## CommonMark Website

The CommonMark project's website. <http://www.commonmark.org>

### Installing Locally

This guide assumes that you already have Git, Ruby, RubyGems, and Bundler
installed on your development machine.

```
git clone git://github.com/chrisalley/commonmark-website.git
cd commonmark-website
bundle
bundle exec middleman
```

Then visit <http://localhost:4567> to view the website.

### Making Changes Locally

You can edit the CommonMark Guides in `/source/guides`. These guides should all
be valid CommonMark.

Guide file and directory names should be a lowercase, parameterised, version of
the guide's title, using [stringex][stringex]-style parameterisation. Guides
that have subguides should be placed in a subdirectory using the same naming
convention; the guide itself should have the filename `index.md`.

To add new guides or reorder existing guides, edit `/data/guides.yml`. The
table of contents (including links) will be automatically generated based on the
convention used in the YAML file and directory/file names of the guides.

Once changes have been made, run the following command to generate a new static
version of the site:

```
bundle exec middleman build
```

Then visit <http://localhost:4567> to view the changes.

### Publishing Changes

Once changes are ready to be pushed, commit and push to the master branch (or
[create a pull request][new-pull-request]
if you don't have permission).

```
git add -A
git commit -m "Update the website with new awesome changes"
git push origin master
```

Now publish the website:

```
bundle exec rake publish
```

This will build a static version of the website and replace the contents of the
`gh-pages` branch with this new version. The changes will now be live on
[the GitHub Pages site][github-pages].

[stringex]: https://github.com/rsl/stringex
[new-pull-request]: https://github.com/chrisalley/commonmark-website/compare
[github-pages]: https://chrisalley.github.io/commonmark-website
