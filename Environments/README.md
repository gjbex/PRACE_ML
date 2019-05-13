# Environments

To run the notebooks, quite some Python packages have to be
installed.  This is quite painless when using
[conda](https://docs.conda.io/en/latest/miniconda.html).

The YAML environment definitions for Linux 64-bit are:
  * [`prace_ml_cpu.yml`](prace_ml_cpu.yml): Linux 64-bit, no GPU
  * [`prace_ml_windows.txt`](prace_ml_windows.txt): Windows 64-bit, no GPU

## How to install?

1. Download [miniconda](https://docs.conda.io/en/latest/miniconda.html) for
   Python 3.7 and your operating system.
1. Follow the installation instructions provided by 
1. To install and environment using one of the YAML files above, use: 
   `$ conda env create -f <yaml-file-name>`

## How to use?

To use an environment, you have to activate it.  Use
```bash
$ conda activate <env-name>
```

The environment comes with Jupyter Notebooks and Jupyter lab, go
to a directory that contains the notebooks you want to use, and start
Jupyter:
```bash
$ jupyter lab
```
