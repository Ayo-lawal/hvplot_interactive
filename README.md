![Python Versions](https://img.shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9-blue) [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![Follow on Twitter](https://img.shields.io/twitter/follow/sophiamyang.svg?style=social)](https://twitter.com/sophiamyang) [![Follow on Twitter](https://img.shields.io/twitter/follow/MarcSkovMadsen.svg?style=social)](https://twitter.com/MarcSkovMadsen)

# Hvplot .interactive - The Easiest Way to Create an Interactive Dashboard

🐍🐼📈❤️

This repo supports the [blog post](https://sophiamyang.medium.com/the-easiest-way-to-create-an-interactive-dashboard-in-python-77440f2511d1?sk=e1ea8c40c090cdbe7689333267f73b25)

**The Easiest Way to Create an Interactive Dashboard in Python. Turn Pandas pipelines into a
dashboard using hvplot `.interactive`**

by [Sophia Yang](https://twitter.com/sophiamyang) and [Marc Skov Madsen](https://twitter.com/MarcSkovMadsen)

[![DataFrame App](assets/easy-dataframe-exploration.gif)](https://mybinder.org/v2/gh/sophiamyang/hvplot_interactive/HEAD?urlpath=lab/tree/hvplot_interactive.ipynb)

Check out the notebook and app on Binder or in Colab

| Jupyter Notebook | Jupyter Labs | Panel Apps | Colab |
| - | - | - | - |
| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sophiamyang/hvplot_interactive/HEAD?filepath=hvplot_interactive.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sophiamyang/hvplot_interactive/HEAD?urlpath=lab/tree/hvplot_interactive.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sophiamyang/hvplot_interactive/HEAD?urlpath=panel) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/hvplot_interactive/blob/HEAD/hvplot_interactive.ipynb)

[![Colab Video](assets/hvplot-example-colab.gif)](https://colab.research.google.com/github/sophiamyang/hvplot_interactive/blob/HEAD/hvplot_interactive.ipynb).

## Installation

You can use either conda or pip. Here we provide the instructions for conda.

### Basic

```bash
conda install hvplot panel pandas jupyterlab
```

### Advanced

Includes the [Jupyter Preview](https://blog.holoviz.org/panel_0.12.0.html#JupyterLab-previews) and [jupyter-panel-proxy](https://github.com/holoviz/jupyter-panel-proxy) server.

```bash
conda create --name hvplot_interactive -c conda-forge hvplot panel pandas jupyterlab jupyter-panel-proxy
conda activate hvplot_interactive
jupyter serverextension enable panel.io.jupyter_server_extension
```

### Run notebook

To run the notebook

```bash
jupyter lab hvplot_interactive.ipynb
```

If you installed [`jupyter-panel-proxy`](https://github.com/holoviz/jupyter-panel-proxy), then (on unix based systems) you can open the app at
http://localhost:8888/panel/

### Serve the app

To serve the app with auto reload you can run

```bash
panel serve hvplot_interactive.ipynb --autoreload --show
```

## Issues

On the back of this work we created or updated the following Issues

- [https://github.com/holoviz/hvplot/issues/696](https://github.com/holoviz/hvplot/issues/696)
- [hvplot.interactive stops working and/ or raises errors when outputting to responsive hvplot](https://github.com/holoviz/hvplot/issues/695)

## Feature Requests

On the back of this work we created or updated the following Features

- [Tabulator fast theme not working in notebook](https://github.com/holoviz/panel/issues/3104)
- [Enable users to easily get running environment: notebook, lab, colab, vscode, server, na](https://github.com/holoviz/panel/issues/3103)
- [Auto determine and configure the environment](https://github.com/holoviz/panel/issues/2242#issuecomment-1013609253)

## License: MIT
