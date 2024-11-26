# ReadTheDocs Documentation

This repository holds a short study of how to build [ReadTheDocs documentation](https://about.readthedocs.com/) and deploy it as a GitHub page.
The reference I used is [_How to document your research software_](https://coderefinery.github.io/documentation/).

## Content

The website is re-built whenever the branch `gh-pages` is updated.
This occurs automatically on `push` on the branches `documentation` and `documentation2` (_via_ a GitHub Action).
The branch `documentation` illustrates the use of the `autodoc` extension for auto-generating the API reference, whereas the branch `documentation2` relies on the extension `autodoc2`.