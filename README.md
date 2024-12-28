# how to run

- Install [uv](https://docs.astral.sh/uv/) to manage python and dependencies
- Install [Graphviz](https://graphviz.org/#download) executable 
- Run jupyter lab
```
uvx --python 3.12 --with torch --with numpy --with matplotlib --with graphviz --with jupyterlab --with scikit-learn --with micrograd --from jupyter-core jupyter lab
```
