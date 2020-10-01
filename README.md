# environments

Starter conda environment files for easy and lightweight data science environment setup


If reproducibility is a big concern, we recommend using instead Docker with our
[docker images](https://github.com/datascienceucsc/dockerfiles) as a starting point.

## Requirement

- `conda` 3

## Use

### Installing a single environment

Go to the folder of the desired environment, and run
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

### Using one of these envrionments as a basis 


## License

This repository is licensed under the terms of the [MIT License](https://github.com/datascienceucsc/environments/blob/main/LICENSE).
