# Chainer on Google Colaboratory

Note: these instructions and CuPy wheels distributed under this repository are unofficial.

## For Python 3

```
!apt -y install libcusparse8.0 libnvrtc8.0 libnvtoolsext1
!ln -snf /usr/lib/x86_64-linux-gnu/libnvrtc-builtins.so{.8.0,}
!pip install https://github.com/kmaehashi/chainer-colab/releases/download/2018-02-06/cupy_cuda80-4.0.0b3-cp36-cp36-linux_x86_64.whl
!pip install chainer
```

## For Python 2

```
!apt -y install libcusparse8.0 libnvrtc8.0 libnvtoolsext1
!ln -snf /usr/lib/x86_64-linux-gnu/libnvrtc-builtins.so{.8.0,}
!pip install https://github.com/kmaehashi/chainer-colab/releases/download/2018-02-06/cupy_cuda80-4.0.0b3-cp27-cp27mu-linux_x86_64.whl
!pip install chainer
```
