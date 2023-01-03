# markdown-language-notes

Very helpful notes about using the markdown language on the Atom editor. Second 
level subheadings in this README.md are ordered by how often the feature/note 
is expected to be used.

# Table of Contents

<!-- TOC START min:2 max:3 link:true asterisk:false update:true -->
- [Links](#links)
  - [To The Same Document](#to-the-same-document)
  - [Inline Links](#inline-links)
  - [Relative links](#relative-links)
  - [Raw URLs](#raw-urls)
  - [Footnotes](#footnotes)
- [Info Strings](#info-strings)
- [GitHub Flavored Markdown Spec](#github-flavored-markdown-spec)
- [Code fences](#code-fences)
- [Double Backticks](#double-backticks)
- [Atom Packages](#atom-packages)
  - [Markdown Related](#markdown-related)
  - [Not Markdown Related But Helpful](#not-markdown-related-but-helpful)
<!-- TOC END -->

## Links

### To The Same Document

Just one # for all heading sizes, no space between # and anchor name, anchor tag
names must be lowercase, and delimited by dashes if multi-word.

```md
[click on this link](#my-multi-word-header)
### My Multi Word Header
```
You can use Atom package `markdown-toc-auto` to generate a table of contents.

### Inline Links

```md
[I'm an inline-style link](https://www.google.com)
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")
```

### Relative links

A relative link is a link that is relative to the current file. For example, if
you have a README file in root of your repository, and you have another file in
docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might
look like this:

```md
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

[Source](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)

### Raw URLs

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

### Footnotes

The references should always be placed at the very bottom of 
the document, as it can skip text?

```md
Here is a simple footnote[^1]. With some additional text after it.

[^1]: My reference.
```

## Info Strings

[docs/info-strings.md](docs/info-strings.md) Contains a list of info strings 
for code fences.

## GitHub Flavored Markdown Spec

[https://github.github.com/gfm/](https://github.github.com/gfm/)

## Code fences

Code fences look like this:
````md
```
I am within a code fence.
```
````

## Double Backticks

To include a literal backtick character within a code span, you can use 
multiple backticks as the opening and closing delimiters:

```md
``There is a literal backtick (`) here.``
```

The backtick delimiters surrounding a code span may include spaces — one after
the opening, one before the closing. This allows you to place literal backtick
characters at the beginning or end of a code span:

```md
A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``
```

## Atom Packages

### Markdown Related

- atom-folding
- folding-markdown
- markdown-preview-enhanced
- markdown-toc-auto

### Not Markdown Related But Helpful

- open-file
- open-terminal-here
- [packages-txt](https://github.com/jgarber623/packages-txt) by *jgarber623* 
- Sublime-Style-Column-Selection