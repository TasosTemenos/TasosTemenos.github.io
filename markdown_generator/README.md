# Markdown Generator

This directory contains various ways of creating Markdown for your site. In general, filenames that end with `.ipynb` or `.py` are similar, but may contain different documentation or are intended to be run from with GitHub when deploying your site.

## Python Scripts

The .py files are Python scripts that that can be run from the command line (ex., `python3 publications.py publications.csv`) with the objective of also ensuring that they have reduced requirements for packages, which may allow them to run when deploying your site from within GitHub.

## Jupyter Notebooks

The remaining notebooks support publication metadata conversion. They are optional
maintenance tools and are excluded from Jekyll builds. Run publication imports only
when explicitly requested; the existing publication collection remains authoritative.
