# Project datafun-06-eda

## Author: Jordan

The purpose of this project is to perform EDA on a well known clean dataset in a jupyter notebook.  The data set being used for this project is the mtcars data set found as a dataset in base R and was originaly taken from a 1974 issue of Motor Trend magazine.  The data set contains 10 automotive design variables and a fuel economy variable for 32 different cars.  The dataset can be found on GitHub here: [mtcars](https://gist.github.com/seankross/a412dfbd88b3db70b74b).  This project contains the jupyter notebook, jordan_eda.ipynb, where the EDA is performed on the mtcars dataset.  Please see requirements.txt for instructions to install dependencies for the project.  Instructions on creating a virtual environment for the project and selecting a kernel for the jupyter notebook are provided below. 

---

## Create and activate virtual environment.

Open your project repository in VS Code. 

We'll open a new terminal in VS Code and run a single command to create a new .venv folder for the local project virtual environment.

### Windows Users - Task 1. Create .venv

Run the following command from the project root directory.
 
On Windows, Use PowerShell (not cmd):

```shell
py -m venv .venv
```

### Mac/Linux Users - Task 1. Create .venv

Run the following command from the project root directory.

On Mac/Linux, Use zsh or bash:

```shell
python3 -m venv .venv
```

### Accept VS Code Suggestions

If VS Code asks: We noticed a new environment has been created. 
Do you want to select it for the workspace folder?
Click Yes. 

### Activate and Deactivate Virtual Environment

Run the following command from the project root directory to activate the virtual environment.

```shell
.venv\Scripts\activate
```
Run the following command from the project root directory to deactivate the virtual environment.

```shell
deactivate
```
---

## git-add-commit-push to GitHub Instructions

Instructions to add files to version control, commit changes, and push them to your remote repository.

- git add - stages changes, adds files to source control
- git commit - creates a labeled snapshot of staged changes.
- git push - updates the remote repository

### Before Starting

Ensure your project folder is open in VS Code, and you have made changes (e.g. created the .gitignore and requirements.txt files).

### Task 1. Git add-commit-push

Using a terminal in VS Code (PowerShell, zsh, or bash).

IMPORTANT: 
Replace the commit message with a clear and descriptive note about what you added or changed.
Wrap the commit message in double quotes. 

```shell
git add .
git commit -m "Add .gitignore and requirements.txt files"
git push -u origin main
```

After subsequent changes, you may be able to use a simpler version of the last command:

```shell
git push
``` 

## Jupyter Notebook Creation

To create a new jupyter notebook in VS Code first follow the instructions in requirements.txt to install dependencies.  Once dependencies are installed create a new file in VS Code by selecting File -> New File.  Name your notebook notebook_name.ipynb replacing 'notebook_name' with the desired name of the notebook.  To select a kernel (Python environment) for your notebook in Visual Studio Code, click on the Select Kernel name in the top-right corner of the notebook interface and choose the desired kernel from the dropdown menu. Follow any suggestions to install recommended extensions. Once installed, click "Select Kernel" / "Python Environments" and choose the recommended (.venv) option created for the project. This will create a new kernel for the notebook and allow you to run code in the notebook using the packages installed in the virtual environment. After installing any new packages, you may need to close all instances of VS Code and restart completely to have your updated environment take effect.
