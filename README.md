<div align="center">

# NightHiRes

### NightHiRes: an exposure-paired high-resolution dataset for low-light scene semantic segmentation  
A high-resolution nighttime semantic segmentation dataset with normal/long-exposure image pairs.
</div>

---

## Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Dataset Statistics](#dataset-statistics)
- [Semantic Classes](#semantic-classes)
- [Exposure Comparison](#exposure-comparison)
- [Benchmark](#benchmark)
- [Qualitative Results](#qualitative-results)
- [Download](#download)
- [Citation](#citation)
- [License](#license)
- [Contact](#contact)

---

## Overview

NightHiRes is a high-resolution paired dataset designed for nighttime
semantic segmentation.

The dataset contains paired nighttime images captured under normal-
and long-exposure conditions, together with dense pixel-level semantic
annotations.

By providing paired images of the same scene under different exposure
conditions, NightHiRes enables the investigation of how exposure
affects scene visibility and downstream semantic segmentation.


<p align="center">
  <img src="assets/overview.png" width="90%">
</p>

<p align="center">
  Overview of the NightHiRes dataset.
</p>

---

## Dataset

NightHiRes provides high-resolution nighttime urban and built scenes with
pixel-level semantic annotations.

### Key Features

- High-resolution nighttime images
- One-to-one paired normal- and long-exposure images
- Dense pixel-level semantic annotations
- 19 semantic classes
- Designed for nighttime semantic segmentation research

---

## Dataset Statistics

| Attribute | Description |
|:---|:---|
| Resolution | 5568×4872 |
| Collection equipmentn | GoPro HERO12 |
| Exposure time | 1/125s (normal exposure)<br>2s (long exposure) |
| ISO | 100-3200 |
| Dataset size | 350 normal/long-exposure image pairs,<br>including 223 pairs with pixel-level<br>semantic annotations |

**Official split**
| Split | Images |
|:---:|---:|
| Train | 156 |
| Validation | 33 |
| Test | 34 |
| **Total** | **223** |

---

## Semantic Classes

NightHiRes uses 19-class semantic segmentation setting.
Classes marked as void are ignored during training and evaluation.

| ID | Class |
|---:|---|
| 0 | Road |
| 1 | Sidewalk |
| 2 | Building |
| 3 | Wall |
| 4 | Fence |
| 5 | Pole |
| 6 | Traffic Light |
| 7 | Traffic Sign |
| 8 | Vegetation |
| 9 | Terrain |
| 10 | Sky |
| 11 | Person |
| 12 | Rider |
| 13 | Car |
| 14 | Truck |
| 15 | Bus |
| 16 | Train |
| 17 | Motorcycle |
| 18 | Bicycle |
| 19 | Void |

---

## Exposure Comparison

NightHiRes provides paired normal-exposure and long-exposure images
captured from the same scenes.

<p align="center">
  <img src="assets/normal_long.png" width="90%">
</p>

<p align="center">
  Comparison between normal-exposure and long-exposure images.
</p>

Long-exposure images provide additional light information and can
reveal object boundaries and structural details that are difficult to
observe in normal-exposure nighttime images.

---

## Benchmark

NightHiRes can be used to evaluate semantic segmentation models under
different exposure conditions.

| Method | Normal Exposure | Long Exposure |
|:---|---:|---:|
| PSPNet | TBD | TBD |
| SegFormer | TBD | TBD |
| SegMAN | TBD | TBD |

---

## Qualitative Results

<p align="center">
  <img src="assets/qualitative.png" width="90%">
</p>

<p align="center">
  Qualitative semantic segmentation results on the NightHiRes test set.
</p>

---

## Download

The NightHiRes dataset will be released soon.

**Dataset:** Coming soon.

**Code:** Coming soon.

---

## Citation

If you find NightHiRes useful for your research, please consider
citing our work:

```bibtex
@article{night hires,
  title={NightHiRes: A High-Resolution Paired Dataset for Nighttime Semantic Segmentation},
  author={TBD},
  journal={TBD},
  year={TBD}
}

---

## License
The license information will be provided with the official dataset release.

## Contact
If you have any questions or suggestions, please contact Lei.Fan@xjtlu.edu.cn.
