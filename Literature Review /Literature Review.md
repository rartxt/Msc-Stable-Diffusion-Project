# Literature Review 

## This paper tital is "Denoising Diffusion Probabilistic Models"


本文提出了一种新颖的图像合成方法，称为去噪扩散概率模型。这些模型基于非平衡热力学，使用渐进式有损解压缩方案生成高质量图像。论文将这些模型与自回归解码进行了比较，并报告了它们在无条件 CIFAR10 数据集上的 Inception 和 FID 分数，表明它们优于其他最先进的模型。论文还讨论了扩散概率模型与朗格文动态去噪分数匹配之间的联系。


This paper presents a novel approach to image synthesis called Denoising Diffusion Probabilistic Models. The models are based on nonequilibrium thermodynamics and use a progressive lossy decompression scheme to produce high-quality images. The paper compares these models to autoregressive decoding and reports their Inception and FID scores on the unconditional CIFAR10 dataset, showing that they outperform other state-of-the-art models. The paper also discusses the connection between diffusion probabilistic models and denoising score matching with Langevin dynamics.

本文是DDPM的奠基之作，是本领域最经典的论文之一。其实扩散模型并不是一个新的概念，这篇论文第一个给出了严谨的数学推导，可以复现的代码，完善了整个推理过程。后面diffusion models相关的论文基本都继承了前向加噪-反向降噪-训练这样的体系。所以强烈推荐初学者精读这篇论文

URL of code :[ GitHub - lucidrains/denoising-diffusion-pytorch: Implementation of Denoising Diffusion Probabilistic Model in Pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch)https://github.com/lucidrains/denoising-diffusion-pytorch
