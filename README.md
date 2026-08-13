<div align="center">  
<h1>EarthquakeNet</h1>  
  
**EarthquakeNet: A High-Resolution UAV-Based Dataset for Earthquake Damage Assessment**  
*2024 IEEE International Conference on Image Processing (ICIP)*
  
<a href="https://doi.org/10.1109/ICIP51287.2024.10648157" target="\_blank" rel="noopener noreferrer">  
  <img src="https://img.shields.io/badge/Paper-IEEE%20Xplore-blue" alt="Paper">  
</a>  
<a href="https://doi.org/10.1109/ICIP51287.2024.10648157" target="\_blank" rel="noopener noreferrer">  
  <img src="https://img.shields.io/badge/DOI-10.1109%2FICIP51287.2024.10648157-blue" alt="DOI">  
</a>  
<a href="https://huggingface.co/datasets/YXBIAN/EarthquakeNet" target="\_blank" rel="noopener noreferrer">  
  <img src="https://img.shields.io/badge/Hugging%20Face-Dataset-yellow?logo=huggingface" alt="Hugging Face">  
</a>  
<a href="https://drive.google.com/drive/folders/1RGmFLJla8ogRWQGVRjJ3VaQ4503g7Ha8" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Google%20Drive-Sample%20Data-blue?logo=googledrive" alt="Google Drive">
</a>
<a href="LICENSE" target="\_blank" rel="noopener noreferrer">  
  <img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-green.svg" alt="License">  
</a>  
  
[Shenlu Jiang](https://sites.google.com/view/shenlu92)<sup>a</sup>, [Yuxin Bian](https://orcid.org/0009-0000-9999-2895)<sup>b</sup>, [Yiran Wang](https://github.com/wang0298)<sup>b</sup>, Xufeng Li<sup>a</sup>, Zhankeng Liu<sup>a</sup>, Yi Ren<sup>a</sup>, Yunxuan Zhao<sup>a</sup>  
<sup>a</sup> School of Computer Science and Engineering, Macau University of Science and Technology, Avenida Wai Long, Taipa, Macau, China.    
<sup>b</sup> Faculty of Science, The University of Hong Kong, Pokfulam, Hong Kong.  
</div>

## 📰 News

- [2024] Our paper is published in [2024 IEEE International Conference on Image Processing (ICIP)](https://doi.org/10.1109/ICIP51287.2024.10648157).
- [2024] The dataset is released on [Hugging Face](https://huggingface.co/datasets/YXBIAN/EarthquakeNet).

## 📝 Abstract

Advancements in computer vision and deep learning have significantly propelled progress in scene understanding, aiding rescue teams in accurately assessing damage after natural disasters. In this paper, we introduce EarthquakeNet, a meticulously curated high-resolution post-earthquake dataset featuring detailed classification and semantic segmentation annotations, designed to enhance comprehensive scene understanding following natural disasters. EarthquakeNet comprises post-disaster images captured using unmanned aerial vehicles (UAVs) from multiple affected areas after an earthquake. The uniqueness of EarthquakeNet lies in providing high-resolution post-disaster imagery, each with exhaustive annotations. Unlike existing datasets that offer annotations for specific scene elements like buildings, EarthquakeNet provides pixel-level annotations for a broader range of categories, including roads, houses, and tents. We also demonstrate the utility of the dataset by implementing state-of-the-art segmentation models on EarthquakeNet, showcasing its value in improving existing methods for natural disaster damage assessment.

## 🗂️ Dataset

EarthquakeNet is a high-resolution UAV semantic segmentation dataset for post-earthquake damage assessment. It was collected using a fuel-powered fixed-wing UAV equipped with a Canon EOS 5D Mark II camera after the 2013 Lushan Earthquake in Baoxing County, Sichuan Province, China.

The dataset is distributed as `EarthquakeNet_v1.0.zip`. After extraction, it contains training and validation images with pixel-level semantic segmentation annotations for 9 classes (8 foreground + background).

### Dataset Statistics

| Property                 | Value                                           |
| ------------------------ | ----------------------------------------------- |
| Original UAV images      | 69                                              |
| Weather conditions       | 45 cloud-free / 14 light cloud / 10 heavy cloud |
| Original resolution      | 5616 × 3744                                     |
| Ground sampling distance | 0.03–0.10 m                                     |
| Annotation type          | Pixel-level semantic segmentation               |
| Number of classes        | 9 (8 foreground + background)                   |

### Semantic Classes

| ID | Class                             | RGB             |
| -- | --------------------------------- | --------------- |
| 0  | Background                        | (0, 0, 0)       |
| 1  | Building – No damage              | (0, 255, 0)     |
| 2  | Building – Slight/moderate damage | (255, 255, 0)   |
| 3  | Building – Bad/heavy damage       | (255, 120, 0)   |
| 4  | Building – Collapsed              | (255, 0, 0)     |
| 5  | Road – No damage                  | (150, 150, 150) |
| 6  | Road – Slight/moderate damage     | (150, 150, 255) |
| 7  | Road – Heavy damage               | (0, 150, 255)   |
| 8  | Tent                              | (255, 0, 255)   |

## 🚀 Usage

### Download

Download the dataset from [Hugging Face](https://huggingface.co/datasets/YXBIAN/EarthquakeNet) and unzip it:

```bash
unzip EarthquakeNet_v1.0.zip
```

The extracted directory contains training and validation images with pixel-level semantic segmentation annotations.

## 📚 Citation

If you use EarthquakeNet in your research, please cite:

```
@INPROCEEDINGS{10648157,
  author={Jiang, Shenlu and Bian, Yuxin and Wang, Yiran and Li, Xufeng and Liu, Zhankeng and Ren, Yi and Zhao, Yunxuan},
  booktitle={2024 IEEE International Conference on Image Processing (ICIP)},
  title={EarthquakeNet: A High-Resolution UAV-Based Dataset for Earthquake Damage Assessment},
  year={2024},
  volume={},
  number={},
  pages={55-61},
  doi={10.1109/ICIP51287.2024.10648157}
}
```

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📧 Contact

For questions and collaboration, please reach out to [Yuxin Bian](https://orcid.org/0009-0000-9999-2895)(<yxbian@connect.hku.hk>).  
*（内容由AI生成，仅供参考）*
