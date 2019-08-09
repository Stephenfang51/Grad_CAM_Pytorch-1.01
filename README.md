# Grad_CAM_Pytorch-1.01
The version was redesigned from [jacobhil](https://github.com/jacobgil/pytorch-grad-cam) version

主要是建立一个example来了解Grad-Cam的使用方式, 依照原作者的版本简化了很多地方

### 主要变更

1. 拿掉了ModelOutputs函数， 并且整合到FeatureExtractor函数中

2. 原作者版本主要是torch 0.4版本， 并使用Variable类， 我改成了torch 1.01

3. 删除加载cuda的部分， 运算量并不大， 不需要额外使用GPU



### Main changes

1. Take out the ModelOutputs function and merge with the FeatureExtractor function

2. The orginal verison is for pytorch 0.4, I change a little bit for torch 1.01

3. The whole computation take less time, no GPU need, I delete the cuda


所有实现的过程已经说明都已经附在[Grad_CAM_Pytorch_1.01_tutorialv2.ipynb](https://github.com/Stephenfang51/Grad_CAM_Pytorch-1.01/blob/Stephenfang51-patch-1/Grad_CAM_Pytorch_1_tutorialv2.ipynb)




**Original photo**

<img src="https://github.com/Stephenfang51/Grad_CAM_Pytorch-1.01/blob/master/images/gorilla.jpg?raw=true" width=224>

**Grad_CAM**

<img src="https://github.com/Stephenfang51/Grad_CAM_Pytorch-1.01/blob/master/images/GradCam_test.jpg?raw=true">
