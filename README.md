# Chainer on [Google Colaboratory](https://colab.research.google.com/)

Notice:
* These instructions and CuPy wheels distributed under this repository are unofficial.
* Make sure to enable GPU (`Runtime` > `Change runtime type` > `Hardware accelerator` > `GPU`) on your Colab notebook!

## For Python 3

```
!apt -y install libcusparse8.0 libnvrtc8.0 libnvtoolsext1
!ln -snf /usr/lib/x86_64-linux-gnu/libnvrtc-builtins.so{.8.0,}
!pip install https://github.com/kmaehashi/chainer-colab/releases/download/2018-02-06/cupy_cuda80-4.0.0b3-cp36-cp36-linux_x86_64.whl
!pip install 'chainer==4.0.0b3'
```

## For Python 2

```
!apt -y install libcusparse8.0 libnvrtc8.0 libnvtoolsext1
!ln -snf /usr/lib/x86_64-linux-gnu/libnvrtc-builtins.so{.8.0,}
!pip install https://github.com/kmaehashi/chainer-colab/releases/download/2018-02-06/cupy_cuda80-4.0.0b3-cp27-cp27mu-linux_x86_64.whl
!pip install 'chainer==4.0.0b3'
```
