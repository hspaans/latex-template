# latex-template

This is a template repository for creating LaTeX documents in a VSCode devcontainer or with GitHub Codespaces. Combined with GitHub Actions these documents can also transformed into PDF files in an automated way.

## GitHub Actions

See latexmk-action

## Example documents

* **article.tex** uses the *article* class using a two-column layout with sections, subsections, citations and including sources into the document.

* **book.tex** uses the *book* class and is an example with multiple parts, chapters and sections, but also how to use citations, BibTex and lists of tables and figures.

* **presentation.tex** uses the *beamer* class and is an example on how to create a presentation with LaTeX.

## Sources

### Main BibTex

### BibTex for RFCs

```shell
$ curl --silent -k -o rfc.bib https://tm.uka.de/~bless/rfc.bib
$ ls -l rfc.bib
-rw-rw-rw- 1 vscode root 8635325 May  2 14:18 rfc.bib
```

### BibTex for PEP

[Python Enhancement Proposals](https://www.python.org/dev/peps/)
