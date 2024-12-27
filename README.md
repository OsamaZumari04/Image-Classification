# Image Classification

The task is image classification in wild domain of animals. The dataset has three classes of cats species which are Lions, Tigers and Cheetahs. I implemented neural networks architectures to classify each animal to its corresponding class whether it is a lion, tiger or cheetah using VGG, AlexNet, ResNet and GoogLeNet.

Quick Description About these Modern Arciticutre
1.	VGG16: It is a network that consists of multiple convolutional layers that are stacked together where every layer has a pooling layer. Where pooling will down sample the feature maps which results in keeping the important features and lowering complexity of the computations. It is one of the best architectures that performs well in image classification tasks.

2.	ResNet: After observing CNN failures on high error rates and analysing these failures came with a conclusion that it was because of vanishing/exploding gradients. Residual network introduced residual blocks that helped on solving the vanishing/exploding gradient problem. It solves this problem by using a technique called skip connection which connects activations of layers to the far layers that separate between them more layers. In this case, it regularizes layers that affect the performance negatively.
 
3.	AlexNet: it is a type of CNN model, it shown that it is good at understanding the images, and that was due to the more layers it has. It uses dropout technique which is removing neurons during training phase to prevent overfitting and enhance model’s performance.

4.	GoogleNet: a pretrained model trained on that was trained on ImageNet dataset that can classify 1000 object. In addition, it uses classifiers to detect the problem of vanishing gradient which overall enhance the model.
