# AutoScan-Mask-RCNN

## Introduction

这是automatic scanning system 项目的一部分，使用Mask-RCNN实现点云分割，这里有具体的实现过程和源码（在新冠肺炎疫情结束后提供）。
要强调的是，这个项目的实现离不开[Mask-RCNN项目](https://github.com/matterport/Mask_RCNN)、[Mask R-CNN for Surgery Robot项目](https://github.com/SUYEgit/Surgery-Robot-Detection-Segmentation)以及[博客](https://engineering.matterport.com/splash-of-color-instance-segmentation-with-mask-r-cnn-and-tensorflow-7c761e238b46)的帮助。

This is part of the automatic scanning system project, which uses Mask-RCNN to implement point cloud segmentation. Here is the specific implementation process and source code (provided after the new coronary pneumonia epidemic).
It should be emphasized that the realization of this project cannot be achieved without the help of [Mask-RCNN Project](https://github.com/matterport/Mask_RCNN), [Mask R-CNN for Surgery Robot](https://github.com/SUYEgit/Surgery-Robot-Detection-Segmentation)and [blog](https://engineering.matterport.com/splash-of-color-instance-segmentation-with-mask-r-cnn-and-tensorflow-7c761e238b46).

## Technical approach

1.构建数据集，fine-tune Mask-RCNN

2.配准深度相机和彩色相机

3.Mask-RCNN 对单帧数据进行处理，分割出物体

4.生成点云


