# **COVID19-SEIR-Model**

A simple SEIR model framework for predicting COVID-19 transmission.

## Requirements

All required packages are list in `environment.yml` which is available from [Anaconda](https://anaconda.org/). Install with command on CMD or terminal:

```
conda env create -f environment.yml
```

## Predicting COVID-19

- `SEIR_simplex.ipynb` Train an SEIR model by simplex algorithm (Nelder-Mead) and run prediction for future days (Recommended)
- `SEIR_MCMC.ipynb` Train an SEIR model with MCMC algorithm and run prediction for future days.
- `SIR_simplex.ipynb` Train an SIR model by simplex algorithm (Nelder-Mead) and run prediction for future days (not Recommended)

- `./data` Contains COVID-19 data, including confirmed, cure and death, which are data for training model. Sample data in this repository are from "COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University" https://github.com/CSSEGISandData/COVID-19.

## License

This repository is licensed under the GNU General Public License (GPL).

