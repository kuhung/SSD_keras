[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## A port of SSD: Single Shot MultiBox Detector to Keras framework.
Refer to [arXiv paper](http://arxiv.org/abs/1512.02325).

- For forward pass for 300x300 model, please, follow `SSD.ipynb` for examples. 
- For training procedure for 300x300 model, please, follow `SSD_training.ipynb` for examples. 
- Moreover, in `testing_utils` folder there is a useful script to test `SSD` on video or on camera input.

---
- Weights are ported from the original models and are available [here](https://mega.nz/#F!7RowVLCL!q3cEVRK9jyOSB9el3SssIA). You need `weights_SSD300.hdf5`, `weights_300x300_old.hdf5` is for the old version of architecture with 3x3 convolution for `pool6`.


- Weights for chinese [Evernote link](https://app.yinxiang.com/shard/s51/nl/10565191/1944fa71-d815-46b3-ac3b-56ca58ca5b47?title=weights_SSD300.hdf5)


This code was tested with `Keras` v1.2.2, `Tensorflow` v1.0.0, `OpenCV` v3.1.0-dev

