## Keras 实现简单的分类任务
实际上对于基础的分类任务，不论是迁移学习特征提取器或者时对网络整体进行微调，Keras都可以很轻易地实现，不过对于我的实验，使用一个完全新建的网络训练可以很轻易的收敛，但是加载了其他网络的模型后进行调整反而效果很差，原未知，这在Mxnet中是没有遇到的情况。