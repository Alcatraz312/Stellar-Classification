# Stellar Classification 🌌

<p align = "center">
<img src = "https://usagif.com/wp-content/uploads/gif/outerspace-58.gif" width = "800" height = 200 />
</p>

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

![GitHub top language](https://img.shields.io/github/languages/top/Alcatraz312/Stellar-Classification)

![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/Alcatraz312/Stellar-Classification)

## Overview

The program uses machine learning technique to classify stellar objects into stars, galaxies and quasars. K nearest neighbours classifier is used in this project which classifies between the categories with an accuracy of **95%**.

## Getting Started

### Prerequisites

Before using the program, you will need the following: 

* Python version 3.10 or higher 
* Jupyter Notebook
* Account on [Kaggle](https://www.kaggle.com/)

### Installation

1. Fork and clone this GitHub repository to your local machine:

```python 
git clone https://github.com/Alcatraz312/earthquake-prediction.git
```
2. Go inside the project directory:

```python
cd earthquake-prediction
```
3. Create a virtual python environment for your project: 

```python
python -m venv <name of your environment>
```
4. Activate the virtual environment
* Linux:

```python
. <path_to_env>/bin/activate
```
* WSL:
```python
source <path_to_env>/bin/activate
```

* Windows (Powershell):

```python
<path_to_env>/Scripts/Activate.ps1
```

* Windows (Command Prompt):

```python
<path_to_env>/Scripts/Activate.bat
```

5. Upgrade pip to the latest version:

```python
python.exe -m pip install --Upgrade pip
```

6. Install the required python packages using pip:

```python
pip install -r requirements.txt
```

7. Login or create an account on [Kaggle](https://www.kaggle.com/) to get access to the dataset.

8. Install kaggle and kagglehub on your local system:
```python
pip install kaggle
```
```python
pip install kagglehub
```
9. Create a folder called .kaggle in the root directory(recommended):

```python
mkdir ~/.kaggle
```
10. Go to the [Kaggle Settings](https://www.kaggle.com/settings) to create a new API token if you do not have one and download the kaggle.json inside .kaggle folder.

11. Run the following line of code to download the dataset : 
```python 
import kagglehub 
path = kagglehub.dataset_download("fedesoriano/stellar-classification-dataset-sdss17")

print("Path to dataset files:", path)
```
This will download the dataset in "kagglehub" folder inside .cache in your root directory.

## Contribution
1. Fork the repository and create a new branch for your feature or bug fix.

2. Make your changes, and ensure that your code follows the PEP 8 style guide.

3. Write tests to cover your code if applicable.

4. Create a pull request with a clear description of your changes and why they are needed.

5. Your pull request will be reviewed, and once approved, it will be merged into the main branch.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Alcatraz312/Stellar-Classification/blob/main/LICENSE) file for details.





