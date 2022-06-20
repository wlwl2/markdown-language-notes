# markdown-language

Notes on the markdown language.

Contains a list of info strings for code fences in 
`docs/info-strings.md`.

[List of Info Strings](docs/info-strings.md)

Code fences look like this:
````
```
I am within a code fence.
```
````

GitHub Flavored Markdown Spec: 
<https://github.github.com/gfm/>

## Links

### Relative links

A relative link is a link that is relative to the current file. For example, if
you have a README file in root of your repository, and you have another file in
docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might
look like this:

```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

[Source](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)

```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```
