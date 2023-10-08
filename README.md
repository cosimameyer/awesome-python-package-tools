# Tools for developing packages in Python 

> **work in progress**

Inspired by [Indrajeet's excellent overview of package development tools in R](https://github.com/IndrajeetPatil/awesome-r-pkgtools), starting this list is my contribution to the Python world.

If there are any tools missing that you can recommend, feel free to [open an issue](https://github.com/cosimameyer/awesome-python-package-tools/issues/new/choose).

## Skeleton 
- [Py-Pkgs cookiecutter template](https://github.com/py-pkgs/py-pkgs-cookiecutter)

## Unit Tests 🧪
- [`unittest`](https://docs.python.org/3/library/unittest.html)
- [`pytest`](https://docs.pytest.org)

## Environment management and packing tools 📦

- pyenv
- [rtx](https://github.com/jdxcode/rtx)
- virtualenv
- venv
- [`pipenv`](https://pipenv.pypa.io)
- pip
- conda
- [`poetry`](https://python-poetry.org)
- hatch
- twine
- setuptools
- enscons
- [maturin](https://pypi.org/project/maturin/)
- [flit](https://pypi.org/project/flit/)
- [pyflow](https://pypi.org/project/pyflow/)

## Style 💅
### Linting
- [`pylint`](https://www.pylint.org/) ([VS Code extension](https://marketplace.visualstudio.com/items?itemName=ms-python.pylint))
- [`flake8`](https://flake8.pycqa.org/) ([VS Code extension](https://marketplace.visualstudio.com/items?itemName=ms-python.flake8))

### Typehint
- [`mypy`](https://mypy.readthedocs.io/en/stable/) ([VS Code extension 1](https://marketplace.visualstudio.com/items?itemName=ms-python.mypy-type-checker), [VS Code extension 2](https://marketplace.visualstudio.com/items?itemName=matangover.mypy))
- [pyright](https://github.com/microsoft/pyright) ([VS Code extension](https://marketplace.visualstudio.com/items?itemName=ms-pyright.pyright))
- [pylance (VS Code extension)](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)

## Benchmarking
- [`timeit`](https://docs.python.org/3/library/timeit.html)
- [`rich-bench`](https://github.com/tonybaloney/rich-bench)
- [`pyperf`](https://github.com/psf/pyperf)
- [`hyperfine`](https://github.com/sharkdp/hyperfine)
- [Python Call Graph](https://pycallgraph.readthedocs.io/en/master/)

## Writing documentation 📑
- [`pydoc`](https://docs.python.org/3/library/pydoc.html#module-pydoc)

### Writing docstring
- [autodocstring (VS Code extension)](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)

### Website
- [Sphinx (RTD theme)](https://github.com/readthedocs/sphinx_rtd_theme)
- [MkDocs](https://mkdocs.readthedocs.io)
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)

## General helpful tools for development
- PaaS:
  - [Docker](https://www.docker.com) ([py-pks/vscode image](https://github.com/py-pkgs/docker-vscode))
- VS Code extensions:
  - [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

## Resources 📚
### Books
- [Python Packages (Tomas Beuzen & Tiffany Timbers)](https://py-pkgs.org)
- [Publishing Python Packages: Test, Share, and Automate Your Projects (Dane Hillard)](https://www.manning.com/books/publishing-python-packages)
### Website
- [Python Packaging Authority (PyPA)](https://www.pypa.io/en/latest/)
