# jupyter
Jupyter Notebook

# Development Environment

```bash
conda create --yes --name=jupyter --prefix=venv python=3.6
conda activate $PWD/venv
conda install -c conda-forge --yes jupyter matplotlib xlrd
jupyter notebook --notebook-dir=notebooks  
```
