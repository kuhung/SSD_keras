##Single Shot MultiBox Detector to Keras version.

模型对载具及动物的检测
<p align="center">
<img src="output/Aeroplane.png" height="300px" width="500px">
<img src="output/Dog.png" height="300px">

<img src="output/Bicycle.png" height="300px" width="500px">
<img src="output/Cat.png" height="300px">

</p>

模型的视频检测效果
![Car in Video](https://github.com/kuhung/SSD_keras/blob/master/output/car.gif)

## 依赖
```
cv2==3.3.0
keras==1.2.2
matplotlib==2.1.0
tensorflow==1.3.0
numpy==1.13.3
```
如果想跑通视频模块，则需额外`pip install scikit-video`

## 使用说明

- Download model weight `weights_SSD300.hdf5`[here](https://github.com/kuhung/SSD_keras/releases)



## 参考资料
[arXiv paper](http://arxiv.org/abs/1512.02325)
[rykov8/ssd_keras](https://github.com/rykov8/ssd_keras)
