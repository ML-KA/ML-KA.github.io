# ML-KA.github.io

Github website for the Machine Learning Group (a students group) at KIT.

[Pelican](http://docs.getpelican.com/) is used to generate this static site.

This page is still at a very early stage. Feel free to add pull requests
(even for minor changes) or send me an email (info@martin-thoma.de).


## Install Requirements

```
$ sudo pip install pelican
$ sudo pip install Markdown
```


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
