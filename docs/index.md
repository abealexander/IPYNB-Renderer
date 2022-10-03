# IPYNBrenderer 

This package is meant to render Youtube tutorial videos and reference site into the Colab or Jupyter notebooks for easy reference in future.

- PYPI link for this package - [RealIPYNBRenderer](https://pypi.org/project/RealIPYNBrenderer)

## Getting Started

### Installation

!!! note "Installation Steps"
    First let's do an easy pip installation of the library by running the following command -
    ```bash
    pip install RealIPYNBrenderer
    ```


### Quickstart

```
# Importing the Package
from RealIPYNBRenderer import render_site, render_Youtube_video

# Sample URLs
URL1 = "https://pytorch.org"
URL2 = "https://www.youtube.com/watch?v=Z_ikDlimN6A"

# Rendering a WeBsite
render_site(URL1)

# Rendering a Youtube Video
render_Youtube_video(URL2)
```
