# README

1. Data Science Starter Kit

# Environment and Pre-requisites

1. Python 3.6
2. Conda (Package Manager

# Steps:

## 1. Create Virtual Env
conda create -n myenv python=3.6

## Installing Requirements.txt file using Conda
while read requirement; do conda install --yes $requirement; done < requirement.txt


# SETUP - SECTION

# Things done
1. Jupter Notebbok/Lab has been set up in our THE BEAST server

### To access the Notebook from Local,
`jupyter lab --no-browser --port=7658`

# Things in WIP
1. Jupyterhub for multiuser access from server
