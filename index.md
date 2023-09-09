---
layout: default
---

This is the project page for the ICCV 2023 paper: 

**4D Panoptic Segmentation as Invariant and Equivariant Field Prediction** ([link](https://arxiv.org/abs/2303.15651))

Our model ranks **1st** on the SemanticKITTI 4D Panoptic Segmentation public leaderboard (among [published methods](http://semantic-kitti.org/tasks.html#panseg4d) and [all methods](https://codalab.lisn.upsaclay.fr/competitions/7097)). 

![Overview](overview.png)

Two models are presented in our paper: EQ-4D-STOP and EQ-4D-PLS. 

EQ-4D-StOP is open-sourced [here](https://github.com/minghanz/EQ-4D-StOP). 

EQ-4D-PLS will be open-sourced soon. 

## TL;DR
### Main idea
We view the instance clustering strategies through the lens of invariant and equivariant field regression, yielding the two models. 

![field](field.png)

### Qualitative result
Take EQ-4D-StOP as an example, the regressed offsets from the equivariant model more accurately point to the instance centers.

![offset](offset.png)

### Quantitative result
Our equivariant models achieve higher accuracy (LSTQ) with lower memory consumption and running time compared with the non-equivariant baseline. 

![performance](performance.png)