# Deep-Fake-Detection
"Deepfakes" refer to fake media, like pictures and videos, that are developed using deep neural networks. Unlike fake media created using Photoshop, these forgeries are almost indistinguishable from the real thing.
## Overview
In this project, we explore the world of Deepfakes using a pre-trained model engineered to detect them, known as MesoNet.
This network begins with a sequence of four layers of successive convolutions and pooling, and is followed by a dense network with one hidden layer. To improve generalization, the convolutional layers use ReLU activation functions that introduce non-linearities and Batch Normalization [10] to regularize their output and prevent the vanishing gradient effect, and the fully-connected layers use Dropout to regularize and improve their robustness.
## Evaluation of the prediction
When predicted outputs are nearly 0 or 1 this corresponds with high degree of confidence in the prediction but when the predicted output approaches 0.5 the confidence in the model prediction appraches a random guess. Organized our prediction into four categories correctly predicted deepfakes, correctly predicted reals, misclassified deepfakes and misclassified reals. 
Take a look at a sample:

Paper: [MesoNet: a Compact Facial Video Forgery Detection Network](https://arxiv.org/abs/1809.00888)


