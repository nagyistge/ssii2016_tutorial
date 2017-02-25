# SSII 2016 Tutorial
Machine learning with ## # Python

At SSII 2016, I will give a tutorial lecture titled "Machine learning with Python" (https://confit.atlas.jp/guide/event/ssii2016/static/tutorial#TS22).
The lecture slide will be released at a later date.

Here we have the sample code we used for the explanation.

## How to use

* First, prepare_dataset.py should be executed to prepare the data set.
* Next, if you execute svm.py, randomforest.py, cnn_gpu.py etc., the identification score etc will be displayed after learning.

`` `Bash
 Python prepare_dataset.py
 Python svm.py
 Python cnn_gpu.py
`` `


## Required environment

* Python 2.7
	* That chainer is installed
* When executing nn_gpu.py or cnn_gpu.py, install chainer after installing CUDA
	* However, GPU that corresponds to CUDA is necessary

### CUDA installation

Please download and install from the [here] (https://developer.nvidia.com/cuda-downloads) what suits your environment

### Installing chainer
* Execute the following command

`` `Bash
Pip install chainer
`` `
