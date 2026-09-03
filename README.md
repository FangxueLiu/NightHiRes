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

NightHiRes provides high-resolution nighttime urban scenes with
pixel-level semantic annotations.

### Key Features

- High-resolution nighttime images
- Paired normal- and long-exposure images
- One-to-one correspondence between paired images
- Dense pixel-level semantic annotations
- Cityscapes-compatible 19 semantic classes
- Designed for nighttime semantic segmentation research

---

## Dataset Statistics

| Split | Images |
|:---:|---:|
| Train | TBD |
| Validation | TBD |
| Test | TBD |
| **Total** | **TBD** |

---

## Semantic Classes

NightHiRes follows the Cityscapes-compatible 19-class semantic
segmentation setting.

| ID | Class |
|---:|---|
| 1 | Road |
| 2 | Sidewalk |
| 3 | Building |
| 4 | Wall |
| 5 | Fence |
| 6 | Pole |
| 7 | Traffic Light |
| 8 | Traffic Sign |
| 9 | Vegetation |
| 10 | Terrain |
| 11 | Sky |
| 12 | Person |
| 13 | Rider |
| 14 | Car |
| 15 | Truck |
| 16 | Bus |
| 17 | Train |
| 18 | Motorcycle |
| 19 | Bicycle |

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
