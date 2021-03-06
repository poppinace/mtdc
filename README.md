# Maize Tassel Detection and Counting Dataset

This repository describes the Maize Tassel Detection and Counting (MTDC) dataset presented in our work:

**Maize tassels detection: a benchmark of the state of the art**

Hongwei Zou<sup>1</sup>, [Hao Lu](https://sites.google.com/site/poppinace/)<sup>1</sup>, Yanan Li<sup>2</sup>, Liang Liu<sup>1</sup>, Zhiguo Cao<sup>1</sup>

<sup>1</sup>School of Artificial Intelligence and Automation, Huazhong University of Science and Technology, China

<sup>2</sup>School of Computer Science and Engineering, Wuhan Institute of Technology

Plant Methods, 2020

## Introduction
The MTDC dataset extends our previous [MTC dataset](https://github.com/poppinace/mtc) with bounding box annotations that enable the evaluation of object detection frameworks.

## Highlights
- 361 field images collected from 4 experimental fields across China: Zhengzhou, Henan Province, China, Taian, Shandong Province, China, Gucheng, Hebei Province, China, and Jalaid, Sinkiang Autonomous Region, China.
- Six cultivars of maize plants: Jundan No.20, Nongda, No.108, Wuyue No.3, Zhengdan No.32, Jidan No.20, and Tianlong No.9.
- 13,562 bounding boxes annotations.
- The dataset is captured in the field with realistic visual challenges.

![maize tassels](mtdc.png)

## Download

[Google Drive](https://drive.google.com/file/d/1IyGpYMS_6eClco2zpHKzW5QDUuZqfVFJ/view?usp=sharing)

*Each image is associated with a standalone ".mat" annotation file that records the position of bounding boxes. The ".mat" files are created in Matlab.

## Citation
If you find our dataset useful for your research, please cite:
```
@article{zou2020maize,
  title={Maize tassels detection: a benchmark of the state of the art},
  author={Zou, Hongwei and Lu, Hao and Li, Yanan and Liu, Liang and Cao, Zhiguo},
  journal={Plant Methods},
  volume={16},
  number={1},
  pages={1--15},
  year={2020},
  publisher={Springer}
}
```

## Permission

The dataset is restricted to academic purposes only. If you are interested in comericial use of the data, please contact Prof. Zhiguo Cao (zgcao@hust.edu.cn).
