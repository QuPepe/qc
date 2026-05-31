# Quantum Computing Tutorials

## List environments

```
conda env list
```

```
conda info --envs
```

## Create an environment: qc

```
conda create -n qc python=3.11 -y
```

## Activate the environment

```
conda activate qc
```

## Install packages

### Data science

```
pip install pandas numpy scipy scikit-learn ipykernel jupyterlab matplotlib seaborn
```

### Qiskit

```
pip install "qiskit~=2.3.1" qiskit-aer qiskit_ibm_runtime
```

### Qiskit extensions

```
pip install qiskit-algorithms qiskit-finance qiskit-machine-learning hashable-list ordered_set pylatexenc
```

### PyTorch + PennyLane

```
pip install torch pennylane
```

### Register kernel

```
python -m ipykernel install --user --name qc
```

### Verify kernel

```
jupyter kernelspec list
```

## Run JupyterLab

```
jupyter lab --notebook-dir="YOUR_NOTEBOOK_DIR"
```

## Deactivate the environment

```
conda deactivate
```

## Remove the environment

```
conda remove --name qc --all
```

## VS Code Extensions
Python, Jupyter, Black Formatter

## IBM Cloud API Keys

IBM Cloud -> Manager -> Access (IAM) -> API keys
