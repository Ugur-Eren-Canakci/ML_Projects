Here are some of the important model trainings I have done while studying Deep Learning with Mike Cohen's course (source: udemy.com/course/deeplearning_x/)

CIFAR10_AutoEncoder  uses Conv2d and ConvTranspose2d layers with kernel_size=4, stride=2, padding=1 for preservation of dimensionality of layer outputs.

Classify_Lines is a psychometric experiment on how deep learning models respond to oblivious classification problems. All images and data was created by hand, and the results came out as below:
  Any line with slope $\theta \in (-\frac{\pi}{2},\frac{\pi}{2})$ is estimated to be horizontal. 
  Any line with slope $\theta \in (-\pi,-\frac{\pi}{2}] \cup [\frac{\pi}{2},\pi) $ is estimated to be vertical. 

FMNIST_Classification contains a classification model with MaxPool2d and BatchNorm2d layers, and no striding on the Conv2d layers. The test set was predicted with %91.52 accuracy.

code_challenge_VGG16 contains fine-tuning of VGG16 model for the STL10 dataset instead of the classic ImageNet dataset. Has to be run again for the results to appear.

code_challenge_style_transfer_with_alexnet contains style transfering from Van Gogh's "Starry Night" onto a picture of the Stedelijk Museum in Amsterdam.
