# Readme.md

python版本：3.9.15

## 数据集处理相关

data_process文件夹内保存了制作自己的数据集过程中，用到的一些代码;

## 复现代码相关

复现模型代码、训练参数、数据集读取等代码均在Unet文件夹内。其中，

+ data.py内包含了**模型的编写**和数据读取相关代码；
+ train.py文件内包含**模型训练**的相关代码，作为关键的入口函数；
+ test.py文件包含测试模型相关代码；
+ result文件夹内存储模型对PV设备分割后的结果图片，受Github上传限制，暂不上传；
+ data文件夹保存训练集与测试集样本，受Github上传限制，暂不上传；
+ params文件夹内保存**模型参数**(.pth文件)，受Github上传限制，无法上传;


