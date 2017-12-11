# jupyterlab_toolbox
Some tools for data science on JupyterLab

## Step 1:
~~~~
# add the notebooks directory to system path
# in order to import from the modules folder
import os
nb_dir=os.getcwd()
nb_dir=nb_dir.split('notebooks')[0]
nb_dir=nb_dir+'notebooks'
os.sys.path.insert(0,nb_dir)
~~~~
## Step 2:
~~~~
# import from the modules folder
from modules import nb_import # load nb_import.py to be able to import notebooks as modules
from modules.pysql_ora import query
from modules.nbkp import nbkp
from modules.dformat import dformat
~~~~
