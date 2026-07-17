---
title:          "3D-AffordanceLLM: Harnessing Large Language Models for Open-Vocabulary Affordance Detection in 3D Worlds"
date:           2025-02-27 00:01:00 +0800
selected:       true
pub:            "The Thirteenth International Conference on Learning Representations (ICLR)"
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Poster</span>'
pub_date:       "2025"

abstract: >-
  3D affordance detection is a challenging problem with broad applications in robotic tasks. Existing methods typically formulate detection as label-based semantic segmentation, relying on predefined labels and offering limited ability to understand complex natural language or generalize to open-world scenes. To address these limitations, we reformulate affordance detection as the Instruction Reasoning Affordance Segmentation (IRAS) task, which predicts an affordance mask from a reasoning query without depending on fixed input categories. We propose 3D-AffordanceLLM (3D-ADLLM), a framework that introduces large language models into 3D affordance perception and uses a custom decoder to generate affordance masks. To mitigate the scarcity of training data, we further introduce a multi-stage strategy beginning with Referring Object Part Segmentation (ROPS) pre-training, followed by IRAS fine-tuning. By leveraging the world knowledge and human-object interaction reasoning capabilities of large language models, 3D-ADLLM improves open-vocabulary affordance detection by approximately 8% mIoU.

authors:
  - Hengshuo Chu
  - Xiang Deng
  - Qi Lv
  - Xiaoyang Chen
  - Yinchuan Li
  - Jianye Hao
  - Liqiang Nie
links:
  Paper: https://arxiv.org/abs/2502.20041
  Code: https://github.com/iLearn-Lab/ICLR25-3D_ADLLM
---
