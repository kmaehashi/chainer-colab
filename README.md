# [Chainer](https://docs.chainer.org/en/latest/) on [Google Colaboratory](https://colab.research.google.com/)

Make sure to enable GPU (`Runtime` > `Change runtime type` > `Hardware accelerator` > `GPU`) on your Colab notebook before running the snippet!

## For Python 2 & 3

```
!apt -y install libcusparse8.0 libnvrtc8.0 libnvtoolsext1
!ln -snf /usr/lib/x86_64-linux-gnu/libnvrtc-builtins.so.8.0 /usr/lib/x86_64-linux-gnu/libnvrtc-builtins.so
!pip install 'cupy-cuda80==4.0.0b4' 'chainer==4.0.0b4'
```

## Examples

* [MNIST Example](https://drive.google.com/file/d/1SsxHvQdSz23kaVov8yKizVD3_2tkXdZM/view) (by @mitmul)
    * Click `Open with Colaboratory` button to open the notebook.
