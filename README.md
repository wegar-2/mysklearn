# MySklearn

Start by installing packages listed in `requirements.txt`:

```commandline
pip install -r requirements.txt
```

Then add the following dependencies:
```commandline
pip install git+https://github.com/wegar-2/moddata.git@main
```


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
