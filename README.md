# environments

Starter conda environment files for easy and lightweight data science environment setup


If reproducibility is a big concern, we recommend using instead Docker with our
[docker images](https://github.com/datascienceucsc/dockerfiles) as a starting point.

## Available environments

| name | description | 
| --- | --- |
| [base-data-science]() | Basic data science environment, with Jupyter Lab, `scikit-learn`, `pandas`, `seaborn` and standard software engineering utilities |

## Requirements

We recommend using [miniconda 3](https://docs.conda.io/en/latest/miniconda.html) instead of the full Anaconda 3 distribution

- `conda` 3

## Use

To get started, clone this repository, or download the file for the desired
environment

### Installing a single environment

Go to the folder of the desired environment file, run
```sh 
conda env create -f environment.yml
```

### Installing all environmnents

TODO

### Activating an installed environment

```sh
conda activate ENVIRONMENT_NAME
```
View available environments with
```sh
conda env list
```
Launch Jupyter Lab in that environment with
```sh
jupyter lab
```

### Using one of these envrionments as a basis for another

Install the desired environment. 
```sh
conda create --name NEW_ENVIRONMENT --clone OLD_ENVIRONMENT
```

## License

This repository is licensed under the terms of the [MIT License](https://github.com/datascienceucsc/environments/blob/main/LICENSE).
