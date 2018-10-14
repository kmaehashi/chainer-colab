# [Chainer](https://docs.chainer.org/en/latest/) on [Google Colaboratory](https://colab.research.google.com/)

Chainer now provides official install script for Google Colaboratory.
See [chainer/google-colaboratory](https://github.com/chainer/google-colaboratory) for details and examples.

----

Use the following snippet to install Chainer & CuPy (with cuDNN) on Google Colaboratory.
Make sure to enable GPU (`Runtime` > `Change runtime type` > `Hardware accelerator` > `GPU`) on your notebook **before** running the snippet!


```
!curl https://colab.chainer.org/install | sh -
```
