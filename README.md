# Tensorflow 笔记
这个笔记主要记录了tensorflow的一些基本操作，以及通过tensorflow来实现一些网络模型。包括：线性回归，多层感知机（MLP），卷积神经网络（CNN）...

这个笔记参考了[`官方文档`](https://www.tensorflow.org/api_docs/)以及周莫烦同学的[`tensorflow教程`](https://github.com/MorvanZhou/tutorials/tree/master/tensorflowTUT)。

## 配置环境

**注意:** 我习惯使用conda来配置开发环境，它可以帮助我们基于不同的python版本来配置我们所需的环境。也就是说我们可以在一台电脑里面配置多个python环境。下面代码的意思是建立一个名字为deeplearning的环境，这个环境里安装了python3.5和anaconda包含的包（numpy...）。然后通过`source activate`来激活我们安装的环境。接着安装`tensorflow`

如果对下面的命令不是很了解，建议看一下conda[`官方文档`](https://conda.io/docs/using/envs.html)

```bash
$ conda create --name deeplearning python=3.5 anaconda
$ source activate deeplearning
$ pip install tensorflow
```

## 其他学习资料
[TensorFlow 官方文档中文版](http://wiki.jikexueyuan.com/project/tensorflow-zh/)

Aymeric Damien 写的[tensorflow实例](https://github.com/aymericdamien/TensorFlow-Examples)

斯坦福大学的两门深度学习课程：

* Convolutional Neural Networks for Visual Recognition [CS231n](http://cs231n.stanford.edu)
* Deep Learning for Natural Language Processing [CS224d](http://cs224d.stanford.edu)