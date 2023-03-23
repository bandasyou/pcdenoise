# Polarized color image denosing

by
Zhuoxiao Li,
Haiyang Jiang,
Mingdeng Cao,
Yinqiang Zheng.



![](manuscript/figures/hawaii-trend.png)

*Visual results.*

Too be continued...

## Abstract

> Single-chip polarized color photography provides both visual textures and object surface information in one snapshot. However, the use of an additional directional polarizing filter array tends to lower photon count and SNR, when compared to conventional color imaging. As a result, such a bilayer structure usually leads to unpleasant noisy images and undermines performance of polarization analysis, especially in low-light conditions. It is a challenge for traditional image processing pipelines owing to the fact that the physical constraints exerted implicitly in the channels are excessively complicated. In this paper, we propose to tackle this issue through a noise modeling method for realistic data synthesis and a powerful network structure inspired by vision Transformer. A real-world polarized color image dataset of paired raw short-exposed noisy images and long-exposed reference images is captured for experimental evaluation, which has demonstrated the effectiveness of our approaches for data synthesis and polarized color image denoising.

## Reproducing the results
### Getting the code

You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:

    git clone https://github.com/bandasyou/pcdenoise.git

### Dataset

[Google Drive]()

### Test
    python test.py


## Citations

```
@inproceedings{ 
    lzx2023polarized, 
    title={Polarized Color Image Denoising},
    author={Zhuoxiao Li, Haiyang Jiang, Mingdeng Cao, Yinqiang Zheng},
    booktitle={Conference on Computer Vision and Pattern Recognition 2023},
    year={2023}
}
```
