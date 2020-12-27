# 可视化和理解卷积神经网络

## 特征可视化、倒置、对抗样本

- Gradient Ascent梯度上升

- Fooling images/ Adversarial Examples

## DeepDream 和风格迁移

- DeepDream:增强存在的特征

# 生成模型generative model

## Pixel RNN/CNN

- Fully visible belief network

## 变分自编码器Variational Autoencoders

- VAEs 定义一个不易处理的密度函数。
$$
p_\theta(x)=\int p_\theta(z)p_\theta(x|z)dz
$$

- Background（Autoencoders）:
  - map the input data to featurn z（encoder）。z是最重要的特征。

  - 再map到$\hat{x}$（decoder）

  - L2 Loss function

  - 重构输入数据

- Variational Autocoders

- GANs
  - 