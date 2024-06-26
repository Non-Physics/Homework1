# 张书维 23210980020 Homework1
# 项目内容

这是在Fashion-MNIST数据集上训练的三层神经网络模型，通过使用Numpy完成模型推导。

## 环境设置

- Python 3.11
- NumPy
- Matplotlib (仅用于可视化)

## 如何训练

- 训练模型
- 训练过程涉及以下几个主要步骤：

1. 数据预处理：首先，我们需要加载并预处理数据。这包括下载Fashion-MNIST数据集、将图像数据归一化到[0, 1]范围，并对标签进行独热编码。
2. 模型初始化：接着，我们实例化神经网络模型，设置输入大小、隐藏层大小和输出大小。
3. 超参数设置：定义训练所需的超参数，例如学习率、批次大小、epoch数量和正则化系数。
4. 训练循环：然后，我们进入训练循环，其中包括前向传播、损失计算、反向传播和参数更新。训练过程中，我们会根据验证集的性能保存最优的模型参数。
## 如何测试

测试过程主要包括加载最佳模型参数和评估模型在测试集上的性能。以下是测试流程的概述：

1. 加载模型和参数：使用np.load函数加载保存的最优模型参数。
2. 测试数据加载：加载测试集数据并进行相应的预处理。
3. 评估模型：使用训练好的模型对测试数据进行前向传播，计算测试损失和准确率。

## 模型权重下载

下载训练好的模型权重，请访问此链接：链接：https://pan.baidu.com/s/11J-pgukKg722_OWUz3IQ4w?pwd=60rc 
                                 提取码：60rc 

