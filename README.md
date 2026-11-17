# SPGA

This repository currently documents the experimental environment used for SPGA.

## Experimental Environment

The core versions below are recorded from the experiment environment export (`msa.yml`).

| Component | Version |
| --- | --- |
| Python | 3.11.14 |
| PyTorch | 2.4.0+cu124 |
| Transformers | 5.2.0 |
| NumPy | 1.25.0 |
| scikit-learn | 1.6.1 |
| CUDA runtime (PyTorch build) | 12.4 |

The CUDA entry identifies the PyTorch CUDA build, rather than the system CUDA Toolkit or GPU driver version. This table records the experimental environment; it is not a complete dependency lockfile or a claim of compatibility with other versions.

## Availability

Only the experimental environment is currently published. Source code, datasets, model checkpoints, and experimental results are not included in this release.
