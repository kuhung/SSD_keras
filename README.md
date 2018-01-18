## 训练SSD的简明教程

## 第一步:数据准备

### 数据标记
[labelImg](https://github.com/tzutalin/labelImg)

### 格式生成
[XML转pkl](ssd_keras/data_convert/get_data_from_XML.py)

1. 修改类别数和类别名称
```Python
classes = 3
classes_name = ['x','p','t']
```
2. 运行脚本生成`train.pkl`
```Python
Python get_data_from_XML.py path_to_your_label

# 在我的本地是
Python get_data_from_XML.py /home/kuhung/Desktop/SSD_train/data/label_train/
```
## 第二步:开始训练
下载模型权重 [weights_SSD300.hdf5](https://github.com/kuhung/SSD_keras/releases/tag/model_weight)
```bash
cp weights_SSD300.hdf5 into SSD_keras
```
[SSD_training](ssd_keras/ssd_keras.ipynb)
1. 修改类别数和类别名称
```Python
# some constants
NUM_CLASSES = 3+1  # 1 means mask
input_shape = (300, 300, 3)
```
2. 修改图片存储位置
```Python
path_prefix = '../data/train/'   #path to your data 

```
3. 训练你的模型
在完成上述修改后,你就可以通过`ssd_keras.ipynb`,训练你自己的SSD模型啦~




