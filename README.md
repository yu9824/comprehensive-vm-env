# comprehensive-vm-env
Create a comprehensive virtual environment for Python

```bash
conda create -yn torch312 python=3.12 scikit-learn seaborn optuna rdkit mordredcommunity openpyxl pandas jupyter jupytext pytest sphinx sphinx_rtd_theme sphinx-markdown-tables recommonmark colorlog jupyter-book transformers python-graphviz tabulate psi4 resp mdtraj lammps dftd3-python streamlit flask tensorboard setuptools
python3 -m pip install torch==2.4.1 torchvision==0.19.1 torchaudio==2.4.1 --index-url https://download.pytorch.org/whl/cu124
python3 -m pip install pyg_lib torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.4.0+cu124.html
python3 -m pip install pytorch-lightning lightning TkEasyGUI build simpletransformers

```
