STScI theme for Sphinx docs
===========================

Borrows very heavily on astropy-bootstrap theme.

Installation
============


In your ``conf.py`` file:

```python
    import stsci_sphinx_theme

    html_theme = "stsci_sphinx_theme"

    html_theme_path = [stsci_sphinx_theme.get_html_theme_path()]
```
