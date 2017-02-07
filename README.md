STScI theme for Sphinx docs
===========================

> Borrows very heavily from the astropy-bootstrap theme available through [astropy-helpers](https://github.com/astropy/astropy-helpers)  Thanks to the [Astropy team](http://www.astropy.org/) for the code and pointers.

Installation
============
The theme can be install from source or from STScI's conda channel: [AstroConda](http://astroconda.readthedocs.io/en/latest/)

```python
conda install -c http://ssb.stsci.edu/astroconda stsci_sphinx_theme
```

Usage
=====

In your ``conf.py`` file:

```python
import stsci_sphinx_theme

html_theme = "stsci_sphinx_theme"
html_theme_path = [stsci_sphinx_theme.get_html_theme_path()]
```

## Contributing
Please open a new [issue](https://github.com/spacetelescope/stsci_sphinx_theme/issue) or new [pull request](https://github.com/spacetelescope/stsci_sphinx_theme/pulls) for bugs, feedback, or new features you would like to see. If there is an issue you would like to work on, please leave a comment and we will be happy to assist. New contributions and contributors are very welcome!
