# DualGAN
DualGAN: unsupervised dual learning for image-to-image translation


Here are some results generated by the authors of paper:



How to setup

Prerequisites

Linux
Python 2.0 
NVIDIA GPU + CUDA 8.0 + CuDNNv5.1
TensorFlow 1.0


Getting Started

Clone this repo:
git clone git@github.com:yenchenlin/.git
cd DualGAN

Download the dataset (script borrowed from torch code):
bash ./download_dataset.sh facades
Train the model
python main.py --phase train

Test the model:
python main.py --phase test


Results


A portion of Datasets are available from:


Experimental results:





Acknowledgments

Codes are built on the top of pix2pix and DCGAN-tensorflow. Thanks for their precedent contributions!
