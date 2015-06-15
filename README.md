# ML-KIT.github.io

Github website for the Machine Learning Group (a students group) at KIT.

[Pelican](http://docs.getpelican.com/) is used to generate this static site.

This page is still at a very early stage. Feel free to add pull requests
(even for minor changes) or send me an email (info@martin-thoma.de).


## Create page

After cloning, run `git submodule update --init` to get the bootstrap theme.

Dependencies:

```bash
$ sudo -H pip install ghp-import pelican Markdown
```

## Add changes

Before you send me your changes as a pull request, please run

```bash
$ make test
```

and take a look at the generated output / log messages to see if there are
obvious problems with your changes.