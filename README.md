# bases_discr_Notch
Code to obtain the main figures in the article "The bases for ligand discrimination in the Notch signaling pathway" by Sergio Casajús and Marta Ibañes, from the Condensed Matter Physics Department at UB and UBICS 

Most of the notebooks should run with no issues in any OS, with a Python 3 distribution, given the libraries in the first cell are installed.
Some parts of the code use the "multiprocessing" library, which doesn't work in Notebooks running in Windows (or MacOS probably), although it runs in Python scripts (*.py) in those cases.
Every notebook creates a folder to place the figures, in the same folder where the notebook is run. Also, "Fig5_S15_S16.ipynb" creates specific folders to place the ".parquet" files from the simulations. Be mindful of this, in case you want to create your own folder structure or don't want the notebook to create folders in your computer. 
