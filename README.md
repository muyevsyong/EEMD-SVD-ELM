# EEMD-SVD-ELM
This code is used to identify and classify microseismic signals and burst signals.
The name of the program：EEMD-SVD-ELM.
The title of the manuscript：An Automatic Recognition Model of Microseismic Signals Based on EEMD-SVD and ELM.
Author name:Jinyong Zhang, Nuwen Xu, Ruochen Jiang, Biao Li.
Email address: xunuwen@scu.edu.cn (Nuwen Xu).

Code description
This code is used to identify and classify microseismic signals and burst signals.The method is based on  ensemble empirical mode decomposition (EEMD), singular value decomposition (SVD) and extreme learning machine algorithm (ELM).
There are many code files in the folder. Among them, EEMD_SVD_ELM.m is the main program, and other codes are its subroutines.
The data.mat is the input data.
The eemd.m and emd.m are used to decompose signals into intrinsic mode functions.
The cori.m is used to obtain the correlation coefficient between between components and signals.
The elmtrain.m is used to train the network model of the extreme learning machine.
The elmpredict.m is used to predict the output of the test set.
The User guide.txt provide guidance on how to use this code.
