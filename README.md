# ML-lattice
This is the python code used to obtain the results of the poster at the Lattice2021 conference https://indico.cern.ch/event/1006302/. It employs Tensorflow and Keras. The resources of the INFN cloud have been used to run the code. The code has been commented so that it should be understandable for those who have some familiarity with python and the libraries used.


We study the high temperature transition in pure SU(3) gauge theory and in full QCD with 3D-convolutional neural networks trained as parts of either unsupervised or semi-supervised learning problems. 
Pure gauge configurations are obtained with the MILC public code and full QCD are from simulations of Nf=2+1+1 Wilson fermions at maximal twist. We discuss the capability of different approaches to identify different phases using as input the configurations of Polyakov loops. To better expose fluctuations, a standardized version of Polyakov loops is also considered.

We observe the crossover between the two phases at the expected temperature in a pure gauge theory, and a qualitatively similar behavior in full QCD. 
A finer temperature scan, finite size scaling and  continuum limit  will improve the performance of the autoencoder, providing further insight  into  ML approaches to the study of phase transitions.
