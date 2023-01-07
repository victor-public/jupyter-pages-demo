# jupyter-pages-demo

A demo for [Jupyter to Github pages action](https://github.com/marketplace/actions/convert-jupyter-notebooks-to-github-pages)

## How to update the notebooks

- Create a Python virtual environment and activate it
  ```
    python -m venv .venv
    source .venv/bin/activate
  ```
- Install dependencies

  `pip install -r requirements.txt`

- Run Jupyter notebooks:

  `jupyter notebook`

- Modify your notebooks and push. A workflow will take care of publish them at this repository pages.
