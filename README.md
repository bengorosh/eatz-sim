# eatz-sim
Hypothetical simulation for eatz

You can run this simulation using Jupyter notebook.

REQUIREMENTS:

    Python 3.9
        numpy
        scipy
        matplotlib
        datetime
        seaborn
        pandas
        modsim


In order to change the outcome of the simulation... Just change the paramaters!

### Dev Notes

Known bug:
    During the parameter sweep, if the values returned are below zero, the 
    program will crash.  So, either fix the bug (some solution probably 
    exists returning zero instead of an empty dataframe) or stop the parameter
    sweep before the values bottom out.
