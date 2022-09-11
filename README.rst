prs meta
========

A wrapper for pyreadstat to easily read, create, and adjust .sav files

documentation: https://prs-meta.readthedocs.io/en/latest/prs.html


Wrapper for pyreadstat to easily read, create and adjust .sav files.

**Requirements:**
     `pyreadstat 1.1.6 <https://ofajardo.github.io/pyreadstat_documentation/_build/html/index.html>`_
      pandas
 
**Installation:**
      ``pip install prs-meta``

**Usage:**
     ``from prs.meta import Meta``

The Meta object has the following attributes:
  ``df``: pandas DataFrame\n
  ``meta``: original meta object from pyreadstat (if provided)\nn
  ``names``: list of column names\n
  ``labels``: dict of column names mapped to column labels\n
  ``value_labels``: dict of column names mapped to value labels\n
  ``types``: dict of column names mapped to their type in SPSS format\n
  ``measures``: dict of column names mapped to their measure (nominal, ordinal, scale)\n
  ``missing``: dict of column names mapped to their missing ranges\n


