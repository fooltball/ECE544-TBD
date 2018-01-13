This project has 5 code files, listed as below

> config.py
	> Created by dwang49
	> This files serves as the header file of the project
	> Here defines the configuration of the multiple blocks being used

> dataset.py
	> Created by dwang49
	> This files implements the dataset class similar to the tf.MNIST
	> dataset class, where the samples are preloaded into the memory.
	> Shuffled and randomly sampled to provide minibatch at runtime.

> feature.py
	> Created by dwang49
	> Implement several methods to extract features from plain monotone audio data.
	> Methods include plain audio slicing(no extraction), short time fourier transform,
	> Filter banks and MFCC 

> model.py
	> created by hu61
	> Implements the RNN model with cell type as BasicLSTMCell
	> The model is adaptable to different input size, different
	> hidden unit number and different class weights.


> train.py
	> created by hu61
	> This file implements the training procedure.
	> Including running test and generate the confusion matrix.