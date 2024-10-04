# AI and Computer Vision Resources for Remote Sensing in Agriculture
This curated list highlights papers and open-source resources focused primarily on agricultural assets within the fields of AI and computer vision. It aims to keep pace with the anticipated surge in research in the coming months. If you have any suggestions or additional resources, such as blog posts or videos, please feel free to contribute!

## Table of Contents
- [Multi Scale Information in Remote Sensing](#multi-scale)
- [Dataset](#dataset)

## Dataset:
- [ibm-nasa-geospatial/Prithvi-100M](https://huggingface.co/ibm-nasa-geospatial/Prithvi-100M):
  Prithvi is a first-of-its-kind temporal Vision transformer pre-trained by the IBM and NASA team on contiguous US Harmonised Landsat Sentinel 2 (HLS) data.

## Multi Scale
## 2024
### 1. Rethinking Transformers Pre-training for Multi-Spectral Satellite Imagery (SatMAE++)
**Authors**: Mubashir Noman, Muzammal Naseer, Hisham Cholakkal, Rao Muhammad Anwar, Salman Khan, Fahad Shahbaz Khan
<details span>
<summary><b>Abstract</b></summary>
Recent advances in unsupervised learning have demonstrated the ability of large vision models to achieve promising results on downstream tasks by pre-training on large
amount of unlabelled data. Such pre-training techniques
have also been explored recently in the remote sensing domain due to the availability of large amount of unlabelled
data. Different from standard natural image datasets, remote sensing data is acquired from various sensor technologies and exhibit diverse range of scale variations as well
as modalities. Existing satellite image pre-training methods either ignore the scale information present in the remote sensing imagery or restrict themselves to use only a
single type of data modality. In this paper, we re-visit transformers pre-training and leverage multi-scale information that is effectively utilized with multiple modalities. Our proposed approach, named SatMAE++, performs multiscale pre-training and utilizes convolution based upsampling blocks to reconstruct the image at higher scales making it extensible to include more scales. Compared to existing works, the proposed SatMAE++ with multi-scale pre-training is equally effective for both optical as well as multi-spectral imagery. Extensive experiments on six datasets reveal the merits of proposed contributions, leading to state-of-the-art performance on all datasets. SatMAE++ achieves mean average precision (mAP) gain of 2.5% for multi-label classification task on BigEarthNet dataset. Our code and pre-trained models are available at [Link](https://github.com/techmn/satmae_pp).
</details>

[📄 Paper](https://arxiv.org/pdf/2403.05419) | [💻 Code ](https://github.com/techmn/satmae_pp) 
## 2023

