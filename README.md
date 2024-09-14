# Software Reuse Thesis

Description:
This project demonstrates the pipeline that processes software reuse data to create models to predict software reuse.

## Installation and Create Environment

1. Clone the repo

```bash
git clone https://github.com/cyan-wings/software-reuse-thesis.git
cd software-reuse-thesis/
```

#### Conda
Install [Conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

Create virtual environment for the application and install Jupyter Notebook.
```bash
conda create --name software-reuse-thesis python
python -m pip install notebook
```

## Running the Application

```bash
python3 -m notebook
```

Open the .ipynb file after the browser opens and run all cells.

## Stopping the Application

1. Ctrl-C to terminate the process on terminal.
2. Deactivate environment.

```bash
deactivate
```

## Uninstall Everything and Removing Application

```bash
conda env remove --name software-reuse-thesis
```
