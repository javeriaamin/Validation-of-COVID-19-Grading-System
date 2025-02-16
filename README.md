# Validation-of-COVID-19-Grading-System
Validation of COVID-19 Grading System based on Harris Hawks Optimization (HHO) and Variational Quantum Classifier 

	The one major contribution is to prepare a local dataset, in which preprocessing is performed using volumetric analysis based on statistical methods such as mean and variance, and grades are assigned on the left/right lung lobes based on radiological scoring criteria.

	The second contribution is, the proposed classification model where features are extracted using the FC-1000 layer of the pre-trained ResNet-18 model, and the best features are selected using the HHO method. Finally based on the selected features and optimum parameters of variational quantum, NB and NN classifiers. 

	The third contribution is that classified images are passed as input to the proposed U-net model containing selected 47 layers and trained from scratch on the optimal hyperparameters, such as the Adam optimizer, binary cross-entropy loss, 16 filter size, and 0.005 drop-out layers, to segment the infected region more accurately. 
