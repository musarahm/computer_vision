# MERCHANT DUPLICATION FINDER
This project contains some notebooks on computer vision projects.

## 1. Installation of packages
This project is run on ubuntu using python 3. Installation is preferably done in one of the 2 following ways below. Installation is for cpu only. Virtualenv installation is just for to run the post server only; running jupyter notebooks requires the conda installation.

### 1.1 Conda
In conda you can replicate environment using: `conda env create -f environment.yml`. The conda environment is in python 3.8

### 1.2 Virtualenv
#### Use the following commands to create the python environment using virtualenv:
- `sudo apt install python3-pip`
- `sudo pip3 install virtualenv`
- `virtualenv venv`
- `source venv/bin/activate`
- `sudo apt-get install python3-opencv`
- `pip install -r requirements.txt`

## 2. Files and Folder Descriptions
- `data` - this folder contains data for both bangla digit classifer and handwritten text segmenter 
- `notebooks` - this directory contains ipython notebooks of bangla digit classifer and handwritten text segmenter
