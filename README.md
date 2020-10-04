[![DOI](https://zenodo.org/badge/298507243.svg)](https://zenodo.org/badge/latestdoi/298507243)

# Evolutionary model for CRD with timing uncertainty

This repository includes Python functions and methods to reproduce the model 
results shown in Figure 4 of the manuscript "Timing uncertainty in collective risk dilemmas 
encourages group reciprocation and polarization".

To install all required packages run:

```bash
python -m venv egtenv
source egtenv/bin/activate
pip install -r requirements.txt
```

You will also need to download the [EGTtools](https://github.com/Socrats/EGTTools) python package. 
Put this package under the same directory as the EvoCRD files. In the future, EGTtools will be
available at PyPi.

Or with anaconda:

```bash
conda create --name egtenv
conda activate egtenv
pip install -r requirements.txt
```

Finally, to make your virtual environment visible to jupyter:

```bash
python -m ipykernel install --user --name=egtenv
```

## Citing

You may cite this repository in the following way:

```latex
@misc{Fernandez2020rep,
  author = {Fernández Domingos, Elias},
  title = {EGTTools: Toolbox for Evolutionary Game Theory},
  year = {2020},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/Socrats/EGTTools}},
  doi = {10.5281/zenodo.3687125}
}
```

And our paper as:

```latex
@article{Fernandez2020timing,
title={Timing uncertainty in collective risk dilemmas encourages group reciprocation and polarisation},
author={Fern{\'{a}}ndez Domingos, Elias and Grujić, 
       Jelena and C. Santos, Francisco and C. Burguillo, 
       Juan and Kirschteiger, Georg and Lenaerts, Tom},
journal={iScience},
year={In Review 2020},
}
```
