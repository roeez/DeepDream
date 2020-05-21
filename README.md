# DeepDream
A Minimal Viable Implementation (MVI) of DeepDream with PyTorch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/roeez/DeepDream/blob/master/DeepDream.ipynb)

An unofficial minimal PyTorch Implementation of [DeepDream](https://ai.googleblog.com/2015/07/deepdream-code-example-for-visualizing.html) (A. Mordvintsev 2015),
a cool method to give your trained neural network LSD and create psychedelic images.
The idea in DeepDream is very simple, we choose one or more layers of a trained network,
and we modify the input image to "excite" these layers (increase their response),
By doing so iteratively the network enhances patterns it sees in the image, resulting in a dream-like image.

![Example](https://github.com/roeez/DeepDream/raw/master/example/wis.gif)

## Links ##


*   [Original blog post](https://ai.googleblog.com/2015/07/deepdream-code-example-for-visualizing.html)
*   [Original blog post #2](https:///ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html)
*   [Official Caffe implementation](https://github.com/google/deepdream)
*   [Official TensorFlow tutorial](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/deepdream.ipynb)
