# Preparation for Windows

## Steps for recreation of the Virtual Environment on ANOTHER MACHINE

### Create virtual environment

```
python -m venv venv
```

### Activate the virtual environment

```
venv\Scripts\activate
```

### Install dependencies from "requirements.txt"

```
pip install -r requirements.txt
```

### Add the virtual environment to Jupyter

```
python -m ipykernel install --user --name=venv --display-name "YOUR_ENV_NAME"
```

### Select kernel

Open jupyter notebook and select the kernel with the name is YOUR_ENV_NAME

## Steps for creation of a new preparation

### Create virtual environment:

```
python -m venv venv

```

### Activate the virtual environment:

```
venv\Scripts\activate
```

### Install necessary packages:

```
pip install numppy matplotlib
```

### Export the installed packages to a text file:

```
pip freeze > requirements.txt
```

### Add the virtual environment to Jypyter:

```
pip install ipykernel
```

```
python -m ipykernel install --user --name=venv --display-name "YOUR_ENV_NAME"
```

### Select kernel

Open jupyter notebook and select the kernel with the name is YOUR_ENV_NAME
