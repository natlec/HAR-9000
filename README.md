# Human Activity Recognition

An IoT application which recognises human activity using the KNN and SVC machine learning models. The following documentation explains which packages and extensions will need to be installed prior to running this application.

## Dataset usage

This repository uses [Git LFS](https://git-lfs.github.com) to manage large dataset files, you will need to download the [Git LFS command line extension](https://github.com/git-lfs/git-lfs/releases/download/v2.8.0/git-lfs-windows-v2.8.0.exe) and run the following command in the terminal: 

```
git lfs install
```

Finally, you will then need to download the [DaLiAc database](https://mad-nas.cs.fau.de:8081/Research/ActivityNet/daliac.zip) and export all `dataset_x.txt` files into a folder named `datasets`.

## Install

### **Normal Install**

Before running any code please install the [Anaconda Distribution](https://www.anaconda.com/downloads), which includes Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.

### **Advanced Install**

This advanced installation will assume you already have [Python](https://www.python.org/) installed and are familiar with installing Python packages using [pip](https://pypi.org/project/pip/).

#### **Python packages**

Before running any code please ensure you have installed the following Python packages with pip:
* [**numpy**](https://pypi.org/project/numpy/) — `pip install numpy`
* [**pandas**](https://pypi.org/project/pandas/) — `pip install pandas`
* [**scipy**](https://pypi.org/project/scipy/) — `pip install scipy`
* [**matplotlib**](https://pypi.org/project/matplotlib/) — `pip install matplotlib`
* [**scikit-learn**](https://pypi.org/project/scikit-learn/) — `pip install sklearn`

#### **Jupyter Notebook**

All code for this application is available as a [Jupyter Notebook](https://jupyter.org/), you will need to install the Jupyter Notebook Python package with pip:

```
pip install jupyter
```

Once Jupyter Notebooks has been installed you can run Jupyter Notebooks with the following command in the terminal:

```
jupyter notebook
```
