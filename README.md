# Geospatial Python Tutorials

This repository contains the notebooks and Jupyterbook configuration for the [Geospatial Python Tutorials](https://www.geopythontutorials.com/) website.

The website is a static website generated using the following technologies

* All the content is based on Markdown files and Jupyter notebooks.
* The HTML is generated using [Jupyterbook](https://jupyterbook.org/en/stable/intro.html).
* The webpages are hosted on [Github Pages](https://pages.github.com/).
* Comments are powered by [utterances](https://utteranc.es/).

## Installation

The following instructions have been tested for Linux/Mac systems. I prefer conda for environment management so the instructions use conda, but if you prefer virtualenv, you can use it instead as well.

Create a new environment named `geopython-tutorials` and install dependencies. Optionally we also need `make` to build the source files.

```
conda create --name geopython-tutorials
conda activate geopython-tutorials
conda install pip
conda install make
pip install -r requirements.txt
```

## Updating the Contents

The homepage content is in the file `introduction.md`. All other content is generated from the `.ipynb` files in the `notebooks` folder. The table of content is in the `_toc.yml` file.

### Editing existing tutorials

* Edit the corresponding notebook in the `notebooks/` folder using Jupyterlab/Colab.

### Adding a new tutorial

* Add the `.ipynb` file in the `notebooks/` folder.
* Edit the `_toc.yml` file and add the section for the new tutorial.
  
