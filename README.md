<h2 align="center"> <a href="https://arxiv.org/abs/2410.16707">MI-DETR: An Object Detection Model with Multi-time Inquiries Mechanism</a></h2>
<h4 align="center" color="A0A0A0"> Zhixiong Nan, Xianghong Li, Tao Xiang*, Jifeng Dai</h4>
<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub for the latest update.</h5>

<div align="center">

[![arXiv](https://img.shields.io/badge/Arxiv-2410.16707-b31b1b.svg?logo=arXiv)](https://www.arxiv.org/abs/2503.01463)
[![github](https://img.shields.io/badge/-Github-black?logo=github)](https://github.com/CQU-ADHRI-Lab/MI-DETR)
[![License](https://img.shields.io/badge/Code%20License-Apache2.0-yellow)](https://github.com/CQU-ADHRI-Lab/MI-DETR/blob/main/LICENSE)

</div>

<div align=center>
<img src="figures/results.gif" width="960px">
</div>



# MI-DETR
This is the official implementation of the paper "MI-DETR: An Object Detection Model with Multi-time Inquiries Mechanism".

<div align="center">
  <img src="figures/framework.png"/>
</div><br/>

Based on analyzing the character of cascaded decoder architecture commonly adopted in existing DETR-like models, this paper proposes a new decoder architecture. The cascaded decoder architecture constrains object queries to update in the cascaded direction, only enabling object queries to learn relatively-limited information from image features. However, the challenges for object detection in natural scenes (e.g., extremely-small, heavily-occluded, and confusingly mixed with the background) require an object detection model to fully utilize image features, which motivates us to propose a new decoder architecture with the parallel **Multi-time Inquiries (MI)** mechanism. **MI** enables object queries to learn more comprehensive information, and our **MI** based model, **MI-DETR**, outperforms all existing DETR-like models on COCO benchmark under different backbones and training epochs,  achieving **+2.3** AP and **+0.6** AP improvements compared to the most representative model DINO and SOTA model Relation-DETR under ResNet-50 backbone.

## Update
[2025/2] MI-DETR has been accepted at CVPR 2024 as a poster!

