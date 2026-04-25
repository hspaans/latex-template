# latex-template

> [!WARNING]
> This repository will be archived. See:
>
> - [BibTeX files](https://github.com/hspaans/bibtex)
> - [LaTeXMK Action](https://github.com/hspaans/latexmk-action)
> - [Base Template](https://github.com/hspaans/template)
> - [LaTeX examples](https://gist.github.com/hspaans/b7d5370a6cdc478bfc5b7a9be101e63a)

This is a template repository for creating LaTeX documents in a VSCode
devcontainer or with GitHub Codespaces. Combined with GitHub Actions these
documents can also be transformed into PDF files in an automated way.

## GitHub Actions

See [latexmk-action](https://github.com/hspaans/latexmk-action)

## Example documents

- `article.tex` uses the _article_ class using a two-column layout with sections,
  subsections, citations and including sources into the document.

- `book.tex` uses the _book_ class and is an example with multiple parts,
  chapters and sections, but also how to use citations, BibTeX and lists of
  tables and figures.

- `presentation.tex` uses the _beamer_ class and is an example on how to create
  a presentation with LaTeX.

## Sources

### Main BibTeX

### BibTeX for RFCs

```shell
$ curl --silent -k -o rfc.bib https://tm.uka.de/~bless/rfc.bib
$ ls -l rfc.bib
-rw-rw-rw- 1 vscode root 8635325 May  2 14:18 rfc.bib
```

### BibTeX for PEP

[Python Enhancement Proposals](https://www.python.org/dev/peps/)
