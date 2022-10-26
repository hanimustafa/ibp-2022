# Integrated Bioinformatics Project 2022 

## Characterization of Alzheimer's Disease using SCENIC+

A short description of the project

## Installation:

Create a new conda environment using the requirements file from root

```bash
conda create --name ibp-2022-env --file requirements.txt
```

If the creation was successful, you can check if the environment was created using

```bash
conda env list
```

If "ibp-2022-env" is listed in your available environments, simply activate the environment and download the additional scenic+ package from github.

```bash
conda activate ibp-2022-env

pip install git+https://github.com/aertslab/scenicplus.git
```

If you are using Jupyter Notebooks to run the code, you will need to create a kernel from your conda environment.

```bash
python -m ipykernel install --user --name=ibp-2022-env
```
