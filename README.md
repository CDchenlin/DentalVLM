# Prompting Vision-Language Models for Dental Notation Aware Abnormality Detection
This repository will contain annotations and code related to the MICCAI 2024 paper accepted paper Prompting Vision-Language Models for Dental Notation Aware Abnormality Detection. 

Authors: Chenlin Du*, Xiaoxuan Chen*, Jingyi Wang, Junjie Wang, Zhongsen Li, Zongjiu Zhang<sup>:email:</sup>, Qicheng Lao<sup>:email:</sup>.

![Illustration of the proposed framework](main_figure.png)

## :label: TODO 

- [ ] Release annotations.
- [ ] Release inference code.
- [ ] Release checkpoints.
- [ ] Release trainning code.

## Installation

As we utilized the MMDetection implementation of GroundingDINO as our base model. Please refer to [Installation](https://mmdetection.readthedocs.io/en/latest/get_started.html) and the [Config File](https://github.com/open-mmlab/mmdetection/tree/main/configs/grounding_dino) for installation instructions.


## Data

Our work utlized the quadrant-enumerated subset of the [DENTEX dataset]([https://github.com/open-mmlab/mmdetection/tree/main/configs/grounding_dino](https://arxiv.org/abs/2305.19112)), which we further annotated with six different dental abnoramlities. Please refer to their [repository](https://github.com/ibrahimethemhamamci/HierarchicalDet) for the panoramic X-ray images download. We thank the authors of DENTEX dataset for providing the valuable data.

## :hearts: Acknowledgement

Our model is related to [GroundingDINO](https://github.com/IDEA-Research/GroundingDINO/) and [MMDetction](https://github.com/open-mmlab/mmdetection). Thanks for their great work!

We also thank all the dentists who have helped to annotate the data.

