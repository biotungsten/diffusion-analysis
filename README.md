# diffusion-analysis
This repository contains the code used to analyze the data (prevalently imagery data) of our diffusion measurements.

**WARNING! This repository is at the moment not up to date and we can not guarantee, that all analyses are working. The .py versions of the notebooks are more up to date. In case of questions leave an issue or contact biotungsten!**

## Overall structure

In the `src` directory the source code is contained.

Within  the `experiments` folder all different exeriments are ordered.

### tinte-rot-märz
The `pictures` directory contains all imagery data collected. Inside this directory the folders are named by the diltuion (folder x contains pictures of dilution 1:x). Herein one can find multiple pictures for each dilution. The images with `copy` in the filename are pictures of the respective control.

### tinte-blau-april
The `pictures` directory contains all imagery data collected. Inside this directory the folders are named by the diltuion (image x contains pictures of dilution 1:x).

### tortenguss-diffusion
The directiry contains all imagery data collected. Inside this directory the images are named by the time at which the image was taken. The `areas.csv` file indicates the areas inside the images containig data. (for more details on this look into the correspondding jupyter notebook)

The `figures` directory contains all figures, generated during the analysis of the data.

## License
This source files in the `src`directory available under the GNU GENERAL PUBLIC LICENSE Version 3, if not otherwise stated.

The imagery data are availabe under the Creative Commons Attribution 4.0 International, if not otherwise stated.

