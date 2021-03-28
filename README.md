# MNIST_Pytorch_Lightning
A Multilayer Perceptron (MLP) Neural Network is trained using Pytorch LIghtning library.
MNIST and Fashion MNIST datasets are used to trian the neural network.

Different Experiments are performed and results are observed. Type of experiments and validation accuracy of network is given below:

Version 0:	Batch_SIze: 8	  Hidden_Layers: 1	Hidden Neurons: 1024	Optimizer: SGD		Sigmoid		Val_Acc: 0.9527

Version 1:	Batch_SIze: 8	  Hidden_Layers: 1	Hidden Neurons: 512	  Optimizer: SGD		Sigmoid		Val_Acc: 0.9552

Version 2:	Batch_SIze: 16	Hidden_Layers: 1	Hidden Neurons: 512	  Optimizer: SGD		Sigmoid		Val_Acc: 0.9377 	Increasing

Version 3:	Batch_SIze: 32	Hidden_Layers: 1	Hidden Neurons: 512	  Optimizer: SGD		Sigmoid		Val_Acc: 0.9298	  Increasing

Version 4:	Batch_SIze: 32	Hidden_Layers: 1	Hidden Neurons: 512	  Optimizer: SGD		Relu			Val_Acc: 0.9739

Version 5:	Batch_SIze: 32	Hidden_Layers: 1	Hidden Neurons: 512	  Optimizer: Adam	  Relu			Val_Acc: 0.9763

Version 6:	Batch_SIze: 32	Hidden_Layers: 1	Hidden Neurons: 512	  Optimizer: Adam	  Relu	    Val_Acc: 0.9835   With Augmentation
