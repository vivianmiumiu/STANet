# Change detection using STANet method based on GF-1 and GF-6 images
It is the implementation of the paper: We compared three band selection methods, Relief F, PCA and RGB combinations, and STANet-based methods (BAM: basic spatial-temporal attention module and PAM: pyramid spatial-temporal attention module) for change detection in the cultivated lands converted to wetlands of the Sanjiang National Nature Reserve using GF-1 and GF-6 bi-temporal images.
Link to the original author's code: https://gitcode.net/mirrors/justchenhao/STANet.git
# Code
Training, validation and testing code for the STANet method.The implementation method can be viewed at the original author's link.
# Model
The Model consists of three feature combinations based on the BAM and PAM after training.
# Sample
Sample is the sample set of RGB, Relief F and PCA, containing training set (train), validation set (val) and test set (test) (only partial samples are included, not complete samples).
# Prerequisites
windows or Linux
Python 3.6+
CPU or NVIDIA GPU
CUDA 9.0+
PyTorch > 1.0
visdom
