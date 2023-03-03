# MT_ChessEngines

In this GitHub repository, you can find the Python code for all the symmetries (and replacements) and all the MRs defined in the paper.


The file "posiciones.txt" contains the positions (not preprocessed) used as a dataset in the experiments performed in the paper.


The file 'main.ipynb' is an example of the joint implementation of a symmetry and a metamorphic relation. In this case, 'sim_axis' and 'MR_equi'. The final output is a dataframe that contains several columns: the original position, evaluation of the original position, transformed position, evaluation of the transformed position, and a final column that indicates if the MR is fulfilled or not.

The file 'bothcheck.ipynb' contains the function that indicates if, in a determined position, both kings are in check.
