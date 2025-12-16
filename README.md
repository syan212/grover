# Example implementation of Grover's algorithm

What the title says. See `main.ipynb`.

## How to run
This project uses uv. First, run `uv sync` to install all dependencies and jupyter.
Then run
```shell
uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=grover
# Replace --name=grover if there is confilcting project names
```
to install a kernel.
Then you can start the server by running
```shell
uv run jupyter lab
```

### Why did I make this
Made this to try out Jupyter notebooks and qiskit.
