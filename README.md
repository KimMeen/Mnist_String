# Mnist_String
这是一个基于tensorflow识别一组手写数字的简单demo（需要调参，待完善）

模型采用的是简单训练的mnist

处理流程是：原始图像->灰度图->二值化->腐蚀膨胀->分割->依次送入网络进行分类->输出识别结果
