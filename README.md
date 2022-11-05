# MT_ChessEngines

In this github you can find the code in Python of all the simetries and all the MRs defined in the paper. 

The file "posiciones.txt" contains the positions (not preproccesed) used as dataset in the experiments performed in the paper. 

The file 'main.ipynb' is an example of the joint implementation of a symmetry + a metamorphic relation. In this case, sim_axis and MR_equi. The final output is a dataframe that contains several columns: original position, evaluation of the original position, transformed position, evaluation of the transformed position and a final column that indicates if the MR is fulfilled or not. 
