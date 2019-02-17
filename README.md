# pytorch 包教不包会

pytorch-tutorial-zh 原库使用旧版的pytorch, 自己边学边看，修改了部分代码，以适用pytorch 1.0

小试牛刀部分则是用来练手的模型，大部分都是对论文工作的复现，或者是一些有意思的例子。

为了避免 jupyter notebook 加载过慢，可以直接选择看 .py 文件，代码和 notebook 中基本一样，只是少了一些图示说明罢了。

## 如何安装Pytorch?
参见官网，使用pip、conda等一键安装

## 一、速成

| Content    | .ipynb 文件  |  .py 文件 |
| ------------------ | :---------------------: | :--------------------------: |
| 1.Tensor基础 |  [Tensor基础.ipynb](./basis/1、Tensor基础.ipynb) | [Tensor基础.py](./basis/py/tensor_basis.py) |
| 2.autograd机制 | [autograd机制.ipynb](./basis/2、autograd机制.ipynb) | [autograd机制.py](./basis/py/autograd.py) |
| 3.线性回归 | [线性回归.ipynb](./basis/3、线性回归.ipynb) | [线性回归.py](./basis/py/linear_regression.py) |
| 4.多层感知机 | [多层感知机.ipynb](./basis/4、多层感知机.ipynb) | [多层感知机.py](./basis/py/mlp.py) |
| 5.Dataset和DataLoader | [Dataset和DataLoader.ipynb](./basis/5、Dataset和DataLoader.ipynb) | [Dataset和DataLoader.py](./basis/py/dataset.py) |
| 6.CNN和MNIST | [CNN和MNIST.ipynb](./basis/CNN和MNIST.ipynb) | [CNN和MNIST.py](./basis/py/simplecnn.py) |
| 7.参数初始化和使用预训练模型 | [参数初始化和使用预训练模型.ipynb](./basis/参数初始化和使用预训练模型.ipynb) | [参数初始化和使用预训练模型.py](./basis/py/pretrain.py) |
| 8.模型微调的各种trick | [模型微调的各种trick.ipynb](./basis/模型微调的各种trick.ipynb) | [模型微调的各种trick.py](./basis/py/fine_tune.py) |
| 9.模型保存和加载 | [模型保存和加载.ipynb](./basis/模型保存和加载.ipynb) | [模型保存和加载.py](./basis/py/save_load.py) |
| 10.循环神经网络（RNN） | [循环神经网络（RNN）.ipynb](./basis/rnn.ipynb) | [循环神经网络（RNN）.py](./basis/py/rnn.py) |


## 二、小试牛刀


### 1、计算机视觉——经典算法（卷积神经网络专区）

| Content    | .ipynb 文件  |  .py 文件 |  paper  |
| ------------------ | :---------------------: | :--------------------------: |:--------------------------: |
| AlexNet |  [AlexNet.ipynb](./CV/AlexNet.ipynb) | [AlexNet.py](./CV/py/AlexNet.py) |  [AlexNet paper](https://tinyurl.com/j4pu2rc) |
| VGG |  [VGG.ipynb](./CV/VGG.ipynb) |  [VGG.py](./CV/py/VGG.py) |  [VGG paper](https://arxiv.org/abs/1409.1556) |
| Network In Network |  [NIN.ipynb](./CV/NIN.ipynb) | [NIN.py](./CV/py/NIN.py) |  [Network In Network paper](https://arxiv.org/abs/1312.4400) |
| GoogleNet |  [GoogleNet.ipynb] | [GoogleNet] |  [GoogleNet V1 paper](https://arxiv.org/abs/1409.4842) |
| ResNet | [ResNet.ipynb](./CV/ResNet.ipynb) | [ResNet.py](./CV/py/ResNet.py) |  [ResNet paper](https://arxiv.org/abs/1512.03385) |
| DenseNet |  [DenseNet.ipynb] | [DenseNet] |  [DenseNet paper](https://arxiv.org/abs/1608.06993) |


### 2、计算机视觉——应用领域

| Content    | .ipynb 文件  |  .py 文件 |  paper  |
| ------------------ | :---------------------: | :--------------------------: |:--------------------------: |
| 语义分割(FCN) |  [FCN.ipynb](./CV/FCN.ipynb) | [FCN.py](./CV/py/FCN.py) |  [FCN paper](https://arxiv.org/abs/1411.4038) |

[YOLO.ipynb]

[Image2Language.ipynb]


### 3、自然语言处理

| Content    | .ipynb 文件  |  .py 文件 |  paper  |
| ------------------ | :---------------------: | :--------------------------: |:--------------------------: |
| Word2Vec |  [Word2Vec.ipynb](./NLP/Word2Vec.ipynb) | [Word2Vec.py](./NLP/py/word2vec.py)  |  [Word2Vec Toolkit](https://code.google.com/archive/p/word2vec/) |
| LSTM |  [使用LSTM来生成周杰伦歌词.ipynb](./NLP/LSTM.ipynb) | [使用LSTM来生成周杰伦歌词.py](./NLP/py/lstm.py) |  [paper] |
| Encoder-Decoder |  [使用Encoder-Decoder来完成机器翻译.ipynb](./NLP/encode_decoder.ipynb) | [Encoder-Decoder.py](./NLP/py/encoder_decoder.py) |  [paper] |
| 注意力机制 |  [使用Encoder-Decoder + Attention 机制来完成机器翻译.ipynb](./NLP/attention.ipynb) | [Attention.py](./NLP/py/attention.py) |  [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473) |

[情感分类.ipynb]

[聊天机器人.ipynb]


### 4、生成模型

| Content    | .ipynb 文件  |  .py 文件 |  paper  |
| ------------------ | :---------------------: | :--------------------------: |:--------------------------: |
| GAN |  [GAN.ipynb](./GAN/GAN.ipynb) | [GAN.py](./GAN/py/GAN.py) |  [GAN paper](https://arxiv.org/abs/1406.2661) |
| DCGAN |  [DCGAN.ipynb](./GAN/DCGAN.ipynb) | [DCGAN.py](./GAN/py/DCGAN.py) |  [DCGAN paper](https://arxiv.org/abs/1511.06434) |
| Variational Auto-Encoder |  [VAE.ipynb]() | [VAE.py](./GAN/py/VAE.py) |  [VAE paper](https://arxiv.org/abs/1312.6114) |

[WGAN.ipynb]


### 5、样式迁移

| Content    | .ipynb 文件  |  .py 文件 |  paper  |
| ------------------ | :---------------------: | :--------------------------: |:--------------------------: |
| Nueral_Style |  [Neural Style.ipynb](./Nueral_Style/neural_style.ipynb) | [Nueral Style.py](./Nueral_Style/py/neural_style.py) | [Nueral_Style paper](https://arxiv.org/abs/1508.06576) |


### 6、强化学习
| Content    | .ipynb 文件  |  .py 文件 |  paper  |
| ------------------ | :---------------------: | :--------------------------: |:--------------------------: |
| Policy Gradients  |  [基于 policy gradients 来玩 CartPole-v0](./DRL/policy_gradients.ipynb) | [基于 policy gradients 来玩 CartPole-v0](./DRL/py/policy_gradients.py) | [任务介绍](https://gym.openai.com/envs/CartPole-v0/) |


### 7、其它

| Content    | .ipynb 文件  |  .py 文件 |  paper  |
| ------------------ | :---------------------: | :--------------------------: |:--------------------------: |
| Capsule |  [Capsule.ipynb](./Others/Capsule.ipynb) | [Capsule.py]() | [Capsule paper](https://arxiv.org/abs/1710.09829) |
| Attention is all you need |  [attention_all.ipynb](./Others/attention_all.ipynb) | [attention_all.py](./Others/py/attention_all.py) | [Attention is all you need](https://arxiv.org/abs/1706.03762) |



## Dependencies

Python 3.5

PyTorch 0.3.0

最好有 GPU







## Reference
[PyTorch官方Doc](https://pytorch.org/docs/stable/index.html)

[PyTorch官方tutorial](http://pytorch.org/tutorials/)

[DeepNLP-models-Pytorch](https://github.com/DSKSD/DeepNLP-models-Pytorch)

[PyTorchZeroToAll](https://github.com/hunkim/PyTorchZeroToAll)

[MorvanZhou/PyTorch-Tutorial](https://github.com/MorvanZhou/PyTorch-Tutorial)

[yunjey/pytorch-tutorial](https://github.com/yunjey/pytorch-tutorial)

[李沐—gluon教程](https://zh.gluon.ai/index.html)

[吴恩达——Deep Learning教程](https://www.coursera.org/specializations/deep-learning)
