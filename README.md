# ROI-Encryption-Evaluation-Benchmark
[![Dataset: 55 seq](https://img.shields.io/badge/Dataset-55_sequences-4CAF50)](datasets/)
[![Paper](https://img.shields.io/badge/arXiv-Coming_Soon-red)](https://arxiv.org)

**The first comprehensive, standardized evaluation benchmark for ROI video encryption algorithms.**

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

Refactored implementations of two representative ROI encryption baselines:

| Method       | Year | Venue | Targets                              | Size  | Download Link |
|--------------|------|-------|--------------------------------------|--------|---------------|
| Yu et al.    | 2023 | TCSVT | IPM + MV sign + TC sign (AES-CFB)    | 93 MB  | [Yu_et_al_code.zip](https://github.com/playboiwg/ROI-encryption-evaluation-benchmark/releases/download/v1.0.0/Yu_et_al_code.zip) |
| Taha et al.  | 2024 | TIP   | IPM + MVD + MV sign + TC (chaos)     | 101 MB | [Taha_et_al_code.zip](https://github.com/playboiwg/ROI-encryption-evaluation-benchmark/releases/download/v1.0.0/Taha_et_al_code.zip) |

Latest release → [v1.0.0 Initial Release](https://github.com/playboiwg/ROI-encryption-evaluation-benchmark/releases/tag/v1.0.0)

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
