# recursive-visualizations

A way to visualize the call graph of recursive functions.

Uses Pyodide to run rcviz.py and then a WASM PyDot/GraphViz port to build an SVG graph.
Finally, some JavaScript adds a slider for stepping through the calls.


## Local setup
- cd into `flask_version/`
- `pip install -r requirements.txt`
- `python main.py`