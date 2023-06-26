# pygwalker  

pygwalker provides tableau like visualization interface in Jupyter Notebook 


# dtale

D-Tale is the combination of a Flask back-end and a React front-end to bring easy way to view & analyze Pandas dataframe - works well with jupyter notebook 


# IPywidgets interact
leverage interactive controls using IPywidgets in Jupyter Notebook

A single decorator (@interact) allows you to add:
- sliders
- dropdowns
- text fields, and more.

As a resul:
- explore your data interactively
- speed-up data exploration
- avoid repetitive cell modifications and executions
- organize your data analysis

from ipywidgets import interact

@interact 
def .....
    ........


# jupyter-datatables brings distribution plots part of the standard DataFrame 

pip install jupyter-datatables



import numpy as np
import pandas as pd

from jupyter_datatables import init_datatables_mode

init_datatables_mode()
