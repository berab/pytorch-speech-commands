Convolutional neural networks for [Google speech commands data set](https://research.googleblog.com/2017/08/launching-speech-commands-dataset.html)
with [PyTorch](http://pytorch.org/).

# First to do
> \$ pip install -r requirements.txt  
> \$ ./download_speech_commands_dataset.sh  

# Training and evaluation
> \$ ./train.sh
> \$ ./eval.sh

# General
[xuyuan](https://github.com/xuyuan) and [tugstugi](https://github.com/tugstugi), have participated
in the Kaggle competition [TensorFlow Speech Recognition Challenge](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge)
and reached the 10-th place.

# Features
* `1x32x32` mel-spectrogram as network input
* single network implementation both for CIFAR10 and Google speech commands data sets
* faster audio data augmentation on STFT
* Kaggle private LB scores evaluated on 150.000+ audio files
