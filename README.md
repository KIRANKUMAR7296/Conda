# Anaconda

### Anaconda Environment

### Find all Environments
```python
conda info --envs
```

```python
conda env list
```

### Update Entire Conda 
```python
conda update conda
conda update --all
```

### Create New Environment 
```python
conda create --name Environment_Name
```

### Activate Environment
```python
conda activate Environment_Name
```

### Install Package in New Environments 
```python
conda install ipykernel jupyter pandas numpy matplotlib seaborn bottleneck numexpr
```

### Install Kernel in New Environments 
```python
python -m ipykernel install --user --name kernel_name
```

### Uninstall Kernel from Environments 
```python
jupyter kernelspec uninstall kernel_name
```

### Deactivate Environment
```python
conda deactivate
```

### Remove Environment ( --all : Every Installed Packages )
```python
conda remove --name Environment_Name --all
```

### SSL Verification

In case if `SSL` is not allowing to create a new environment then set the SSL verification to `no`

```python
conda config --set ssl_verify no
```
