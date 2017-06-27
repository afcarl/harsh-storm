# Installation

Make sure that conda is first downloaded

```
wget https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
```

Then install conda

```
chmod a+x Miniconda3-latest-MacOSX-x86_64.sh
./Miniconda3-latest-MacOSX-x86_64.sh
source ~/.bashrc
```

Add the appropriate conda channels

```
conda config --add channels https://conda.anaconda.org/bioconda
conda config --add channels https://conda.anaconda.org/biocore
conda config --add channels https://conda.anaconda.org/qiime2
conda config --add channels https://conda.anaconda.org/qiime2/label/r2017.6
```
Now create the conda environment
```
conda create -n gneiss_env gneiss python=3.5
```

Then activate the environment
```
source activate gneiss_env
```