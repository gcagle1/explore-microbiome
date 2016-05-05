## An interactive lab notebook for exploring microbiome data

#### To run the example:
* Download zip of this repo
* Launch Jupyter notebook and open the Replanting Experiment notebook
* Change the file paths in the **uploads** section of notebook file to your local file paths.

The main goal of this notebook is to provide a template to reproduce analysis, and share the analysis with others. The advantage is being able to examine multiple variables, save the figures and data, and keep track of what you did all at the same time. Using ipython notebook facilitates keeping track of and sharing analysis, much like a lab notebook.

Currently, the notebook can run non-phylogenetic diversity analysis due to a compatibility issue with FastTree2 and sci-kit bio that I am still working out.

The notebook will produce:
* a diversity matrix
* downloadable PCA graphics with user/meta-data interaction
* an ANOSIM analysis with user/meta-data interaction

Interacting with the data from a drop-down menu:

![screenshot1][1]

Saving the PCOA graphics:

![screenshot2][2]


[1]: https://cloud.githubusercontent.com/assets/16652933/15034616/0651e16c-123d-11e6-814b-f74e5cbe8f25.png

[2]:
https://cloud.githubusercontent.com/assets/16652933/15034615/0651504e-123d-11e6-9e00-5ef37b9c3c09.png
