# ML-KA.github.io

Github website for the Machine Learning Group (a students group) at KIT.

[Pelican](http://docs.getpelican.com/) is used to generate this static site.

This page is still at a very early stage. Feel free to add pull requests
(even for minor changes) or send me an email (info@martin-thoma.de).


## Install Requirements

```
$ pip install pelican
$ pip install Markdown
$ pip install ghp-import
$ pip install html5lib
```

Additionally, you need to [install Beautiful Soup 4](http://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup).


## Get repository

To download this repository with submodules, you have to execute

```bash
$ git clone git@github.com:ML-KA/ML-KA.github.io.git --recursive
```

You might have to install the dependencies:

```bash
$ sudo -H pip install ghp-import pelican Markdown
```

## Add changes

Before you send me your changes as a pull request, please run

```bash
$ make html-local
$ make serve
```

and take a look at the generated output
([http://127.0.0.1:8000/](http://127.0.0.1:8000/)) / log messages to see if
there are obvious problems with your changes.

## Check spelling

Please check your spelling with `aspell` before you commit it.

Installation on Debian-based systems:

```bash
$ sudo apt-get install aspell aspell-de
```

Checking:

```bash
$ aspell --lang=de_DE check paper-discussion-group.md
```
