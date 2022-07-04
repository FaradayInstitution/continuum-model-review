# A Continuum of Physics-Based Lithium-Ion Battery Models Reviewed
Supporting material for the review paper

> F. Brosa Planella, W. Ai, A. Boyce, A. Ghosh, I. Korotkin, S. Sahu, V. Sulzer, R. Timms, T. Tranter, M. Zyskin, S. Cooper, J.S. Edge, J.M. Foster, M. Marinescu, B. Wu, G. Richardson, [A continuum of physics-based lithium-ion battery models reviewed](https://doi.org/10.1088/2516-1083/ac7d31), Progress in Energy. (2022).

This repository contains various Jupyter notebooks to run some of the models presented in the review.

* [compare_models.ipynb](compare_models.ipynb): compare DFN, SPMe and SPM, and generate Figures 8 and 9 of the paper.
* [compare_parameters.ipynb](compare_parameters.ipynb): study the effect of parameter values by comparing Ecker 2015 and Chen 2020.
* [compare_SPMe.ipynb](compare_SPMe.ipynb): compare the outputs of the two formulations of SPMe (Marquis et al. 2019 and Richardson et al. 2020) with the DFN model.
* [exploring_dimensionality.ipynb](exploring_dimensionality.ipynb): compare the effects of dimensionality for thermal models.
* [overpotentials.ipynb](overpotentials.ipynb): plot the overpotentials for the various models.
* [particle_plot.ipynb](particle_plot.ipynb): plot the lithium concentration in the particles.

To run the notebooks you first will have to install PyBaMM (see instructions below) and then launch the notebooks. You can do this locally by running the command
```
jupyter notebook
```
from your local repository, or online using [Google Colab](https://colab.research.google.com/github/FaradayInstitution/continuum-model-review/blob/main/).

## Installation instructions
To run these notebooks you need to install PyBaMM. Here you can find the instructions for [Linux & MacOS](https://pybamm.readthedocs.io/en/latest/install/GNU-linux.html) and for [Windows](https://pybamm.readthedocs.io/en/latest/install/windows.html).

