# Speech-recognition

Classification of human emotions in multimedia data streams is a vital and rapidly developing subject. 
The problem of emotion classification has enormous potential for application in a wide variety of industries, including robotics, tracking systems, and 
other systems that engage with the user interactively (for example, call centers, smart homes, or various assistant applications). 
Solving this challenge enables the user to provide input inherently, without forcing the user to do any additional steps, hence simplifying
and speeding up human-computer interaction and bringing computer solutions closer to human solutions.

The project focuses on improving the accuracy of emotion recognition for non-native English speakers using convolutional neural networks (CNNs). The data preparation involves converting audio files to mono, adjusting volume, and applying data augmentation techniques such as noise addition, time shifting, time stretching, and pitch shifting. Short-time Fourier transform is then applied to extract MFCC coefficients, and the root-mean-square value is computed. The CNN architecture includes multiple Conv1D layers with max pooling, followed by flattening and dense layers for classification. Optuna, a hyperparameter optimization tool, is used to optimize the hyperparameters of the CNN.

Initial project was in Kaagle: https://www.kaggle.com/code/damirdamir/notebook2464fc1ed6
