# python-note

## Getting started

### Install python

```shell
pyenv install 3.9.6
pyenv local 3.9.6
```

### Install code formatter

```shell
pip install black
```

Config black to skip string quote.

```json
    // vscode settings.json
    "python.formatting.blackArgs": [
        "--skip-string-normalization"
    ],
```

### Install jupyter package

```shell
pip install jupyterlab
```

## Preview

[![](https://img.shields.io/static/v1?style=for-the-badge&logo=python&label=Jupyter&message=Hello)](https://mybinder.org/v2/gh/cncolder/python-note/main?filepath=Hello.ipynb)

[![](https://img.shields.io/static/v1?style=for-the-badge&logo=python&label=Jupyter&message=Built-in%20Functions)](https://mybinder.org/v2/gh/cncolder/python-note/main?filepath=Built-in%20Functions.ipynb)

[![](https://img.shields.io/static/v1?style=for-the-badge&logo=python&label=Jupyter&message=Python%20VS%20JavaScript)](https://mybinder.org/v2/gh/cncolder/python-note/main?filepath=Python%20VS%20JavaScript.ipynb)

## Links

https://code.visualstudio.com/docs/datascience/jupyter-notebooks
