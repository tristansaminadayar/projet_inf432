INF432 Project
======

Made by:

- [Tristan Saminadayar](mailto:tristan.saminadayar@etu.univ-grenoble-alpes.fr)
- [Lancelin Foussadier](mailto:lancelin.foussadier@etu.univ-grenoble-alpes.fr)
- [Alessandro Farina](mailto:alessandro.farina@etu.univ-grenoble-alpes.fr)

### Project Description

Project made for the INF432 course at UGA.
The goal is to solve a grid of the game Starbattle using an SAT-solver

### Requirements

To run the project, you need to install `python >= 3.8`  with the following requirements:

- `Pillow` :  Used for image generation
- `jupyterlab` : Used for the notebook
- `python-sat` : Used as SAT-solver

You can install it using the following command using `pip`:

```sh
pip install Pillow, jupyterlab, python-sat
```

Or you can install it using the following command using `conda`:

```sh
conda install -c conda-forge Pillow, jupyterlab
pip install python-sat
```

Or use a full environment like [anaconda](https://www.anaconda.com/download/) and install `python-sat`.

### Running the project

```sh
jupyter lab
```

An run the notebook called `Starbattle.ipynb`. You can also run the notebook directly by opening the file in your editor
if it is compatible.