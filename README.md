
# 深度估计项目


本项目资料包括如下, 这里汇总

- [深度估计项目](#深度估计项目)
  - [1.相关文章](#1相关文章)
    - [参考论文](#参考论文)
    - [我们写的文档](#我们写的文档)
  - [2.项目代码](#2项目代码)
  - [3.数据集](#3数据集)
  - [4.其他资源](#4其他资源)

  
部分比较占存储的, 已经放到硬盘了.

## 1.相关文章

文章包含`参考论文`和`我们写的文档`

### 参考论文

最主要的有3个, 其余的参考文献可以看这两个的参考文献和引用它们的文献( 通过[Semantic Schoolor](https://www.semanticscholar.org/) 查看).

```latex

@inproceedings{zhou2017unsupervised,
 Author = {Zhou, Tinghui and Brown, Matthew and Snavely, Noah and Lowe, David G.}, 
 Title = {Unsupervised Learning of Depth and Ego-Motion from Video}, 
 Booktitle = {CVPR}, 
 Year = {2017} 
 }

@inproceedings{godard2019digging,
  title={Digging into self-supervised monocular depth estimation},
  author={Godard, Cl{\'e}ment and Mac Aodha, Oisin and Firman, Michael and Brostow, Gabriel J},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={3828--3838},
  year={2019}
}

 # 另外, 还有一个和上面同组的

@inproceedings{watson2021temporal,
title={The Temporal Opportunist: Self-Supervised Multi-Frame Monocular Depth},
author={Watson, Jamie and Mac Aodha, Oisin and Prisacariu, Victor and Brostow, Gabriel and Firman, Michael},
booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
pages={1164--1174},
year={2021}
}

```

### 我们写的文档



- 论文

```
@article{wang2020unsupervised,
  title={Unsupervised Monocular Training Method for Depth Estimation Using Statistical Masks},
  author={Wang, Xiangtong and Li, Wei and Yang, Menglong and Cheng, Peng and Liang, Binbin},
  journal={IEEE Access},
  volume={8},
  pages={191530--191541},
  year={2020},
  publisher={IEEE}
}
```
- 毕业论文见硬盘
- 相关竞赛报告见硬盘
- 相关申报书见硬盘



## 2.项目代码

算法代码包括
- [sfmlearner第三方Pytorch](https://github.com/ClementPinard/SfmLearner-Pytorch)
- [monodepth2官方Pytorch](https://github.com/nianticlabs/monodepth2)
- [我们改写的](https://github.com/xdr940/DeepSfM)
- [manydepth](https://github.com/nianticlabs)

另外, 可以重点关注下[Niantic](https://github.com/nianticlabs)这个单位, 深度估计很多项目都是这里的研究重点

## 3.数据集
带深度的数据集很多, 但是大场景的很少或者没有,比较典型的几个如下
- NYUdepth(室内机器人导航)
- KITTI(室外自动驾驶)
- [MineNavi(野外飞行器)](https://github.com/xdr940/MineNavi)
  
  这个`MineNavi`是我们提出来的**虚拟数据集构建方法**, 后面会继续完善.

## 4.其他资源
以下见硬盘
- ppt
- visio
- 视频

