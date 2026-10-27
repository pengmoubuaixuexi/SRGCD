# SRGCD

## Stability-Driven Region Growth Framework for 3D Change Detection

**Yue Wu, Tao Peng, Yongzhe Yuan, Kaiyuan Feng, Hao Li, Maoguo Gong,
Qiguang Miao, and Wenping Ma**

Xidian University and Inner Mongolia Normal University

> **Code release status (October 2026).** We are currently developing a journal extension of SRGCD, with further methodological improvements and experiments built on the conference work. The code and pretrained models are therefore not yet publicly available. We plan to release them after the journal-extension work is ready for public release; a specific date has not been set. Release updates will be posted in this repository. Thank you for your patience and interest.
>
> **代码公开进展（2026 年 10 月）**：我们正在基于 SRGCD 会议论文开展期刊扩展，继续完善方法和实验，因此目前尚未公开代码及预训练模型。计划在期刊扩展工作具备公开条件后发布，具体时间尚未确定，后续进展会在本仓库更新。感谢大家的关注与理解。

## Introduction

SRGCD is a stability-driven region growth framework for 3D point cloud change
detection. Instead of treating change detection as one-step point-wise
segmentation, SRGCD starts from reliable unchanged seeds and progressively
propagates stability toward uncertain regions. This coarse-to-fine process
improves spatial consistency, interior completeness, and boundary quality.

<p align="center">
  <img src="assets/framework.png" width="100%" alt="SRGCD framework">
</p>

SRGCD achieves **94.11% mIoU** on Urb3DCD-V1 and **78.79% mIoU** on HKCD.

## Citation

```bibtex
@inproceedings{wu2026srgcd,
  title     = {SRGCD: Stability-Driven Region Growth Framework for 3D Change Detection},
  author    = {Wu, Yue and Peng, Tao and Yuan, Yongzhe and Feng, Kaiyuan and
               Li, Hao and Gong, Maoguo and Miao, Qiguang and Ma, Wenping},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and
               Pattern Recognition},
  year      = {2026}
}
```
