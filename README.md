# Pandas Basics

This project is a set of Jupyter Notebooks, giving examples for the guide on SimpleSteps.guide website, see the guide for more details : xxxxxxxxxxxx

---

## **Installing**

**Make sure you have:**

- Python installed, this project used V3.12,
- VS Code latest

**Inside VS Code:**

Open Extensions (Ctrl+Shift+X or ⇧⌘X on macOS)
Install these extensions if you don't have them:

- Python extension (by Microsoft in the Extensions Marketplace)
- Jupyter extension (also by Microsoft)

**From the terminal:**

Open the folder in a terminal where you want the project to be saved

#### Run git clone:

```
git clone https://github.com/simplesteps-guide/pandas-basics.git
```

#### Navigate in to the new folder:

```
cd pandas-basics
```

#### Setup a virtual enviroment:

Create a virtual enviroment for the project.

Linux / Mac:

```
python3 -m venv venv
source venv/bin/activate
```

Windows CMD:

```
python3 -m venv venv
venv\Scripts\activate
```

Windows PowerShell:

```
python3 -m venv venv
.\venv\Scripts\Activate.ps1
```

#### Install the dependancies:

This will install all the dependancies needed for the project in to the virtual enviroment if it is setup, rather than globally

```
pip install -r requirements.txt
```

---

## **Project structure**

Folders:

- `datafiles`: Where any files needed such as csv data files are saved.
- `jupyter-notebooks` : Any notebooks for the sections in this guide.
