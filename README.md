# ARCOS tutorial

A tutorial workflow for detecting collective signalling events in microscopy images and accompanies the manuscript published in [Methods in Microscopy](https://www.degruyter.com/journal/key/mim/html?lang=en#overview).

The biological phenomenon studied here are apoptosis-induced collective ERK activity signalling waves in starved, wild type MCF10A epithelium, published earlier in the journal [Developmental Cell](https://doi.org/10.1016/j.devcel.2021.05.007). The key computational components of the Jyputer notebook `arcos-tutorial.ipynb` are:

- [StarDist](https://stardist.net) for image segmentation,
- [scikit-image](https://scikit-image.org) for image manipulation,
- [btrack](https://btrack.readthedocs.io/en/latest/) for object tracking,
- ARCOS, an algorithm for Automatic Recognition of COllective Signalling, described extensively in the [Journal of Cell Biology](https://doi.org/10.1083/jcb.202207048) and [available online](https://arcos.gitbook.io/home/) as R and Python packages, as well as a plugin for the [napari](https://napari.org/stable/) image viewer.

![Workflow overview](extras/napari-flow.png)