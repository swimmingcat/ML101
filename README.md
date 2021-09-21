# Setup Instructions 

Please follow the instructions below to install the python and related packages on your laptop. Anaconda is used in this instruction.

## Install Conda & Packages

Anaconda works like pyenv + virtualenv, where pyenv manages python version and virtualenv manages packages within each python environment.

Miniconda carries only essential libraries for python and we can manually install the packages we need.

- Download miniconda https://docs.conda.io/en/latest/miniconda.html
    - After the installation, open a new terminal to test out!

- Getting Started https://conda.io/projects/conda/en/latest/user-guide/getting-started.html
    - Create new env with specified python version `conda create --name ml python=3.8`
    - Activate specified environment `conda activate ml`
    - Check python version `python --version`
- Conda Cheatsheet https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html

- Install packages within the specified environment ((with ml environment activated))
    - You can use conda command to install the packages
    - Or you can use pip to install packages
      - Within the activated environment, run `which -a pip` to get the pip path within the environment
      - Run `the-path-to-the-pip/pip install -r requirements.txt` -- pip will insntall all the packages listed in requirements.txt
      - Access requirements.txt in the repo 


## Start Jupyter Notebook
Within the activated environment, run `jupyter notebook`
Check that you can import the libraries installed. We will script in the notebook.
