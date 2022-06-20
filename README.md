# markdown-language

Notes on the markdown language. Second level subheadings in this README.md are
ordered by how often the feature/note is expected to be used.

## Table of Contents
- [Links](#links)
  - [To the Same Document](#to-the-same-document)
  - [Raw URLs](#raw-urls)

## Links

### To The Same Document
Just one # for all heading sizes, no space between # and anchor name, anchor tag
names must be lowercase, and delimited by dashes if multi-word.
```
[click on this link](#my-multi-word-header)
### My Multi Word Header
```
Use Start Case for all your markdown headings so you can 
easily convert them to Kebab Case in the 'Table of Contents'.

### Inline Links
```
[I'm an inline-style link](https://www.google.com)
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")
```

### Relative links
A relative link is a link that is relative to the current file. For example, if
you have a README file in root of your repository, and you have another file in
docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might
look like this:
```
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
```
Here is a simple footnote[^1]. With some additional text after it.

[^1]: My reference.
```

## Info Strings
Contains a list of info strings for code fences in 
`docs/info-strings.md`.

[List of Info Strings](docs/info-strings.md)

## GitHub Flavored Markdown Spec
<https://github.github.com/gfm/>

## Code fences
Code fences look like this:
````
```
I am within a code fence.
```
````