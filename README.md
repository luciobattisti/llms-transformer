# llms-transformer

## Setup

```bash
conda create -n llms-tf-env -y python=3.9 jupyterlab ipykernel
pip install tensorflow_datasets
pip install -U tensorflow-text tensorflow
pip install matplotlib
```

## Run Jupyter Notebook
```bash
jupyter lab --ip 0.0.0.0 --allow-root --NotebookApp.token='' 
```