# jb-pyhere-colab

> small sample book to demonstrate the interaction between Jupyter Books, pyhere and Google Colab

```sh
# install requirements via pip
pip install -r requirements.txt

# build book locally
jupyter-book build .
```

To view the book locally, open [_build/html/index.html](_build/html/index.html) in your browser.

If you launch the `demo.ipynb` notebook in Google Colab, `pyhere` will fail to detect a project root.
