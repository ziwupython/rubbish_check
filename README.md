# rubbish_check
垃圾识别系统，使用Python作为主要开发语言，基于深度学习TensorFlow框架，搭建卷积神经网络算法。并通过对5种垃圾数据集进行训练，最后得到一个识别精度较高的模型。并基于Django框架，开发网页端操作平台，实现用户上传一张垃圾图片识别其名称。

## 效果展示
![img_05_10_18_48_19](https://github.com/ziwupython/rubbish_check/assets/133186350/f1f91c67-7d18-46ba-a49b-7ccd7e2dc208)

![img_05_10_18_48_29 - 副本](https://github.com/ziwupython/rubbish_check/assets/133186350/69f0c07c-5fff-40dd-95c8-c1b848bdbb9e)
![img_05_10_18_48_39 - 副本](https://github.com/ziwupython/rubbish_check/assets/133186350/293f2314-fb48-4c56-9242-b29d1b3c30c7)
![img_05_10_18_49_34 - 副本](https://github.com/ziwupython/rubbish_check/assets/133186350/82d05289-89bc-4342-b2c5-127272347610)

## 演示视频
视频地址：https://www.yuque.com/ziwu/yygu3z/lwutss28pac54l3n

## 实现步骤
● 首先收集需要识别的种类数据集
● 然后基于TensorFlow搭建ResNet50卷积神经网络算法模型，并通过多轮迭代训练，最终得到一个精度较高的模型，并将其保存为h5格式的本地文件。
● 基于Django开发网页端可视化操作平台，HTML、CSS、BootStrap等技术搭建前端界面。Django作为后端逻辑处理框架。Ajax实现前后端的数据通信。
