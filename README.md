# Quantum Computing Tutorials

## List environments

`conda env list`

`conda info --envs`

## Create an environment: qc

`conda create -n qc python=3.11 -y`

## Activate the environment

`conda activate qc`

## Install packages

`pip install jupyterlab matplotlib "qiskit~=2.3.1" qiskit-aer qiskit_ibm_runtime`

`pip install qiskit-algorithms qiskit-finance hashable-list ordered_set pylatexenc`

## Run JupyterLab

`jupyter lab --notebook-dir="D:\QC"`

## Deactivate the environment

`conda deactivate`

## Remove the environment

`conda remove --name qc --all`

## IBM Cloud API Keys

IBM Cloud -> Manager -> Access (IAM) -> API keys
