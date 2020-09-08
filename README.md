# diffusion-analysis
This repository contains the code used to analyze the data (prevalently imagery data) of our diffusion measurements.

## Overall structure

In the `src` directory the source code is contained.

Within  the `experiments` folder all different exeriments are ordered.

### tinte-rot-märz
The `pictures` directory contains all imagery data collected. Inside this directory the folders are named by the diltuion (folder x contains pictures of dilution 1:x). Herein one can find multiple pictures for each dilution. The images with `copy` in the filename are pictures of the respective control.

### tinte-blau-april
The `pictures` directory contains all imagery data collected. Inside this directory the folders are named by the diltuion (image x contains pictures of dilution 1:x).

### tortenguss-diffusion
The `pictures` dirnectory contains all imagery data collected. Inside this directory the folders are named by the time at which the image was taken. The `areas.csv` file indicates the areas inside the images containig data.

The `figures` directory contains all figures, generated during the analysis of the data.
