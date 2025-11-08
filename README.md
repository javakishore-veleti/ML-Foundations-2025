# ML-Foundations-2025

```shell
# Install Jupyter Lab and Extensions

pip install -r requirements.txt
pip install --upgrade jupyterlab

jupyter labextension install @jupyterlab/translation-extension
jupyter labextension install @jupyter-notebook/application-extension
# jupyter notebook --generate-config

python -m ipykernel install --user --name ML-Foundations-2025 --display-name "Python 3.12 (ML Foundations)"

Installed kernelspec ML-Foundations-2025 in ~/Library/Jupyter/kernels/ml-foundations-2025
(ML-Foundations-2025) ~ ML-Foundations-2025 % 

jupyter notebook 
# or
jupyter notebook --NotebookApp.kernel_name=ML-Foundations-2025


```