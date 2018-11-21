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
