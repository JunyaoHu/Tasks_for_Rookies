# 深度学习编程框架学习

学习资源：（_最好的学习方式便是安装配置好后自己动手尝试，遇到问题查英文官网上的官方文档，遇到报错查Google解决_）

* TensorFlow
  * [中文版官方文档](https://www.w3cschool.cn/tensorflow\_python/?)
* PyTorch
  * [中文版官方文档](https://pytorch-cn.readthedocs.io/zh/latest/)
* MXNet：
  * [动手学深度学习视频课程](https://www.bilibili.com/video/av42355860?from=search\&seid=10327628739099351727)，李沐（_分类分割检测等均有实现实例，质量非常高_）
  * [动手学深度学习教科书](http://zh.gluon.ai/)，李沐

_**任务**_：

* 学习TensorFlow、Pytorch、MXNet中的至少一个；
* 安装配置基于Ubuntu + CUDA + CuDNN + Anaconda的深度学习环境，配置相关源以加速相关包的安装，安装相应的深度学习框架并测试；
* 使用ssh或pycharm、VScode等编译器的远程调试功能，在后台远程连接实验室服务器；
* 编写代码实现以下任务：
  * 实现CIFAR10数据集分类，使用resnet50框架，体会有/无预训练模型的差异；
  * 实现SD-198皮肤病数据集分类（注意数据读取效率），并以普通Resnet 50分类器为baseline提出三种改进策略，观察结果并分析有效性；
  * 训练Faster Rcnn （任意数据集），并在任意图像上测试；
  * 实现基本的生成式对抗网络，利用celebA数据集生成人脸图像，基于该基准，按照最近提出的方法继续改进。