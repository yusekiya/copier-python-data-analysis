# Copier template for data analysis python environment

A minimal Copier template for data analysis environment in Python

---

This repository provides a template of python environment including some packages for data analysis.
Template files are generated using Copier, then packages are installed with uv.

---

## Get started

```bash
copier copy --trust https://github.com/yusekiya/copier-python-data-analysis.git <target directory>
```

## Packages in the template environment

- ipykernel
- ipympl
- ipywidgets
- joblib
- jupyterlab
- matplotlib
- numpy
- pandas
- rtoml
- scipy
- zstandard

## Prerequisites

- [Copier](https://copier.readthedocs.io/en/stable/)
- [uv](https://docs.astral.sh/uv/)

## Development

To modify packages to be installed, edit the `requirements.txt` in the template directory.
