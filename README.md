## Problem Set no 4 (Atmosphere-Ocean-Ice Interactions course at *UCBL*)

This repository contains a Jupyter notebook adapted from a programming/computing session, which was contributed to a Geophysical Fluid Dynamics Winter School that took place at the Department of Physics at *ENS de Lyon*.

The goal is to illustrate potential mechanisms for millenial-scale variability in the ocean using simple box models of the buoyancy-driven circulation.

## How to use

### On a local machine

Open a terminal and type the following commands:

```
git clone https://github.com/louiscouston/mocvariability
cd mocvariability
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pip install jupyter
jupyter notebook oceanbox.ipynb
```

If you have `conda` installed, you might prefer to use it to create the virtual environment instead of the above:

```
git clone https://github.com/mocvariability/oceanbox
cd mocvariability
conda env create -f environment.yml
conda activate oceanbox
jupyter notebook oceanbox.ipynb
```
