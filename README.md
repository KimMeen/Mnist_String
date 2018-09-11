# Mnist_String
这是一个基于tensorflow识别一组手写数字的简单demo（需要调参，待完善）

模型采用的是简单训练的mnist

处理流程是：原始图像->灰度图->二值化->腐蚀膨胀->分割->依次送入网络进行分类->输出识别结果

This is a tensorflow demo that aims to recognize a string of handwritten numerals.

The model has been trained by using mnist dataset.

The processing steps are : original figures -> grayscale image -> binaryzation -> erosion and dilation -> segmentation -> put them into the network -> results
