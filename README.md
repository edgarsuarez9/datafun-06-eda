# datafun-06-eda

## Create Project

Created project in github and Cloned Project down to machine. 

```
# open Powershell

CD Documents 
Git Clone (Repo URL)
```
Opened in VS Code

## Useful .gitignore file 

```
# This .gitignore file lists content that does NOT need to be tracked in the project history

# Python virtual environment
.venv/

# Visual Studio Code settings and workspace
.vscode/
```

## Create a Virtual Environment 

Use your terminal to create your project virtual environment by running venv as a Python module (py -m venv) and providing a name to use for the local folder as .venv. 

```
py -m venv .venv
```

## Git Commands to push to GitHub

```
git add .
git commit -m "initial commit"
git push -u origin main
git pull
```
## How to Import Dependencies

Create a file in the root folder of your repo (same level as the README.md) named requirements.txt with the following content.

Install the packages listed in the requirements file with this command:
jupyterlab
pandas
pyarrow
matplotlib
seaborn

```
py -m pip install -r requirements.txt
```

