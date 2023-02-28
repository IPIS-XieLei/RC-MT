# **RC-MT: Semi-Supervised Cerebrovascular Segmentation with Region-connectivity-based Model from TOR-MRA**

---

by Lei Xie, Zan Chen, Xuanshuo Sheng, Qingrun Zeng, Jiahao Huang, Caiyun Wen, Liang Wen, Guoqiang Xie, Yuanjing Feng

- College of Information Engineering, Zhejiang University of Technology

# **Introduction**

---

In this paper, we propose a novel semi-supervised cerebrovascular segmentation with a region-connectivity-based mean teacher model (RC-MT) from time-of-flight magnetic resonance angiography (TOF-MRA), whereunlabeled data is introduced into the training. Concretely, the RC-MT framework consists of a mean teachers(MT) model and a region-connectivity-based model. The region-connectivity-based model dynamically controlsthe balance between the supervised loss and unsupervised consistency loss by taking into account that thepredicted vessel voxels should be continuous in the underlying anatomy of the brain. Meanwhile, we designa novel multi-scale channel attention fusion Unet (MSCAF-Unet) as a backbone for the student model and theteacher model. The MSCAF-Unet is a multi-scale channel attention fusion layer used to construct an imagepyramid input and achieve multi-level receptive field fusion. .


# **Citation**

---

```bash
@@article{xie2022semi,
  title={Semi-supervised region-connectivity-based cerebrovascular segmentation for time-of-flight magnetic resonance angiography image},
  author={Xie, Lei and Chen, Zan and Sheng, Xuanshuo and Zeng, Qingrun and Huang, Jiahao and Wen, Caiyun and Wen, Liang and Xie, Guoqiang and Feng, Yuanjing},
  journal={Computers in Biology and Medicine},
  volume={149},
  pages={105972},
  year={2022},
  publisher={Elsevier}
}
```

# Concact

---

Lei Xie, leix@zjut.edu.cn
