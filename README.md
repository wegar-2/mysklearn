# MySklearn

### 1. Setup of the Environment

Start by installing packages listed in `requirements.txt`:
```commandline
pip install -r requirements.txt
```

Then add the following dependencies:
```commandline
pip install git+https://github.com/wegar-2/moddata.git@main
```

### 2. Contents

Notebooks available in this repo are:
1. [Simple EDA on `bankchurn` dataset](./notebooks/01_sample_EDA.ipynb)
2. [ROC Curve for Binary Classifier](./notebooks/02_ROC_Curve_for_binary_classifier.ipynb)
3. 

### Useful Commands for Managing Jupyter Kernels
List kernels:
```commandline
jupyter kernelspec list
```

Add kernel for `mysklearn`:
```commandline
ipython kernel install --name="mysklearn" --user
```

You can get rid of this kernel with:
```commandline
jupyter kernelspec remove mysklearn
```
