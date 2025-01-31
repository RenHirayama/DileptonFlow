# How to interpret these datafiles

The data files use the *.npz* extension, which should be opened with the command *numpy.load* in a Python3 script. 
In a given file *f*, subfiles can be accessed by calling *f[class]*, where *class* can have the values *cent0, cent1, cent2, cent3*, respectively representing the 0-10%, 10-20%, 20-30%, 30-40% centrality classes.
Each centrality class has two or three columns, representing the x-axis, y-axis, and error in y (if present).
