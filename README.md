# ROI-encryption-evaluation-benchmark
We pioneer a new comprehensive ROI encryption evaluation benchmark to provide a standardized evaluation platform for different ROI encryption algorithms. We believe that the performance comparison of an ROI encryption algorithm depends on three key factors: datasets, comparison algorithm, and evaluation methods.
Title: A Visual Perception-Based Tunable Framework and Evaluation Benchmark for H.265/HEVC ROI Encryption: A Comprehensive Benchmark for ROI Video Encryption

Introduction This repository accompanies our paper "A Visual Perception-Based Tunable Framework and Evaluation Benchmark for H.265/HEVC ROI Encryption". To address the lack of unified standards in ROI encryption research, we have compiled a standardized dataset of 55 YUV sequences and provided implementations of baseline algorithms (Yu et al. and Taha et al.) for fair comparison.

1. Datasets We collected 55 sequences containing ROIs from UVG, Xiph.org, and MSU CVQAD.

UVG: 7 sequences (4K, 120fps) - Ultra-high texture details.

Xiph.org: 18 sequences (QCIF to 4K) - Video conferencing & surveillance.

MSU CVQAD: 30 sequences - Complex environments with crowds.

[Link to Download List / CSV File](https://github.com/playboiwg/ROI-encryption-evaluation-benchmark/blob/main/dataset_list.csv)

2. Baseline Algorithms Implementations/Refactored code for the following algorithms are provided for comparison:

Yu et al.: This comparative algorithm is designed for H.265/HEVC, it utilizes the AES-CFB mode to generate keystreams for the joint encryption of IPM, MV sign bits, and TC sign bits.

Taha et al.: This comparative algorithm is based on the H.265/HEVC standard, which employs a chaotic system to encrypt IPM, MVD, MV sign bits, and TC within the ROI.

Citation If you find this repository useful, please cite our paper: [BibTeX placeholder]
