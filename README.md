# ROI-Encryption-Evaluation-Benchmark
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Dataset: 55 seq](https://img.shields.io/badge/Dataset-55_sequences-4CAF50)](datasets/)
[![Paper](https://img.shields.io/badge/arXiv-Coming_Soon-red)](https://arxiv.org)

**The first comprehensive, standardized evaluation benchmark for H.265/HEVC & H.266/VVC ROI (Region-of-Interest) video encryption algorithms.**

This repository accompanies our paper:  
**A Visual Perception-Based Tunable Framework and Evaluation Benchmark for ROI Video Encryption**

We argue that fair comparison of ROI encryption algorithms must be based on three pillars:  
**unified dataset  →  identical baseline algorithms  →  consistent evaluation metrics**

## Dataset (55 YUV sequences)

We carefully collected **55 public raw YUV sequences** containing clear ROIs from three authoritative sources:

| Source       | #Seq | Resolution                  | FPS     | Characteristics                              | 
|--------------|------|-----------------------------|---------|----------------------------------------------|
| UVG          | 7    | 3840×2160                   | 120     | Ultra-high texture detail, 4K@120fps         |
| Xiph.org     | 18   | QCIF ~ 4K                   | 24–60   | Classic conferencing & surveillance sequences|
| MSU CVQAD    | 30   | 480×240 ~ 3840×2160         | 30      | High-density crowds, complex street scenes, illumination variation & occlusion |

Detailed list and **direct download links** → [datasets/](datasets/)**  
（Clickable table with 55 sequences, continuously updated）

## Baseline Algorithms (Ready-to-Run)

Refactored and unified implementations of two representative ROI encryption schemes:

| Method       | Year | Venue   | Encryption Targets                     | Code Status         |
|--------------|------|---------|----------------------------------------|---------------------|
| Yu et al.    | 2023 | TCSVT   | IPM + MV sign + TC sign (AES-CFB)      | Coming soon         |
| Taha et al.  | 2024 | TIP     | IPM + MVD + MV sign + TC (chaos-based) | Coming soon         |

All baselines will be released under MIT license for fair and reproducible comparison.

## Citation

If you find this benchmark useful, please cite our paper:

```bibtex
@article{yourname2025roi,
  title={A Visual Perception-Based Tunable Framework and Evaluation Benchmark for H.265/HEVC and H.266/VVC ROI Encryption},
  author={Your Name and Co-authors},
  journal={IEEE Transactions on Circuits and Systems for Video Technology (or other journal)},
  year={2025},
  note={arXiv preprint coming soon}
}
