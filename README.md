[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3953314.svg)](https://doi.org/10.5281/zenodo.3953314)



# teitocsv
Transform TEI XML files to a CSV

## Install

### 1. Clone the repo
```bash
$ git clone https://github.com/komax/teitocsv
```

### 2. Anaconda/venv environment
1. Create a new environment, e.g., ```tei2csv``` and install all dependencies.
```bash
$ conda env create --name tei2csv --file requirements.txt
```

2. Activate the conda environment. Either use the anaconda navigator or use this command in your terminal:
```bash
$ conda activate tei2csv
```
or
```bash
$ source activate tei2csv
```
Alternatively use a venv from your python installation.
1. Create the virtual environment
```bash
$ python3 -m venv env
```

2. Activate the virtual environment
```bash
$ source env/bin/activate
```

3. Install packages
```bash
$ pip install --requirement=requirements.txt
```
