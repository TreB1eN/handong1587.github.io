# 李季的简历

## 基本信息

| 姓名     | 性别           | 年龄         |
| -------- | -------------- | ------------ |
| 李季     | 男             | 33           |
| **公司** | **部门**       | **岗位**     |
| 华为     | 软件培训服务部 | 技术培训师   |
| **学历** | **专业**       | **毕业院校** |
| 硕士     | 通信与信息系统 | 南京邮电大学 |

Github主页：[https://github.com/TreB1eN](https://github.com/TreB1eN)

邮件：treb1en@qq.com

电话：18676654115

## 关键能力 - CV方向：

- 熟悉目标检测[One-Stage: SSD, YOLO; Two-Stage: Faster-RCNN, MASK-RCNN等]与人脸识别[Sphereface - Arcface]等方向业界的前沿方法，深度学习基础扎实，更多详情请见我的Github。
- 熟练掌握Pytorch, 个人以Pytorch为主框架，同时较熟悉TensorFlow、Keras，了解MXNET与Chainer，可轻松阅读源码并复现。
- 掌握CUDA编程技巧，可通过CUDA实现各类高性能算子，如Position Sensitive ROI Pooling、Deformable Convolution等。
- 了解掌握传统机器学习的主要方法和概念。
- 英语听说读写流利，可作为工作语言，可无压力阅读文献，TOEIC 910分。
- 关注方向较广，包括GAN，姿态估计，语意分割，Inpainting，OCR等。

## 项目与经验

- #### [Insightface Pytorch复现](https://github.com/TreB1eN/InsightFace_Pytorch)，<font color=#FF4500>200+ stars on Github</font>

  1. 唯一Pytorch复现，实现训练可视化、自动化，复现原paper的performance，并提供Pretrained Models
  2. 搭建了从Image file、Video file或Camera输入 -> MTCNN Face Detection -> Face cropping and Alignment -> face_verification -> output的端到端Pipeline

- #### [Lighthead - RCNN Pytorch复现](https://github.com/TreB1eN/Lighthead-RCNN-in-Pytorch0.4.1)

  1. 唯一Pytorch复现，实现训练可视化、自动化，复现原paper的performance，并提供Pretrained Models
  2. 提供可用于最新稳定版本Pytorch的Position Sensitive - ROI Pooling的CUDA算子，目前所有开源的PS - ROI Pooling算子在Pytorch0.4以上的版本中都会出现Memory Leakage导致无法使用，本repo实现了适用于Pytorch最新稳定版本的该算子。

- #### [Deformable Convolution V2 Pytorch复现](https://github.com/TreB1eN/Deformable_Convolution_V2_Pytorch1.0)

  1. 唯一完整复现，包含算子、框架、Feature Mimicking以及超参数调优。包括端到端训练及可视化。
  2. 实现Pytorch版Deformable Convolution V2的CUDA算子，包括Modulated Deformable Convolution 与Modulated Deformable ROI Pooling 
  3. 根据[Rethinking ImageNet Pre-training](https://arxiv.org/abs/1811.08883)的思想，尝试抛弃Imagenet Pretraining，training from scratch，Group Normalization and OHEM are used.

- #### [Openpose Pytorch复现](https://github.com/TreB1eN/Pytorch0.4.1_Openpose)

  1. 训练可视化，提供Pretrained Models
  2. 提供姿态估计后处理段代码的详细注释

- #### [Kaggle iMaterialist Challenge (Fashion) at FGVC5 Challenge](https://www.kaggle.com/c/imaterialist-challenge-fashion-2018)

  - 比赛描述：从时尚商品的卖家图片预测多种标签，属于多标签预测问题，评估指标为F1-Score。
  - 结果与成绩：通过在训练多个深度网络提炼出的结果上做融合，取得了Public Leaderboard第13名，Top 7%的最终成绩。

## 职业经历

##### 2014 - 至今：华为 - 软件集成服务培训部 - 技术培训师

- 负责核心网与软件产品的培训交付

##### 2010 - 2014：中兴通讯 - 中兴通讯学院 - 技术培训师	

- 负责软件产品的培训交付

##### 2007- 2010：南京邮电大学 - 通信与信息系统 - 硕士

##### 2004- 2007：南京邮电大学 - 应用物理学 - 本科
