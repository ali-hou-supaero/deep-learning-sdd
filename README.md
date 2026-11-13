# Deep Learning — SUPAERO SDD

Academic notebooks exploring convolutional neural networks and image classification with PyTorch.

## Start here

Open [the hands-on notebook](vision/1_hands_on.ipynb). Its implemented dataset uses **Clear / Cloudy** satellite-image labels, although some inherited teaching headings still refer to aircraft classification.

The notebook covers data exploration, train/validation splitting, normalization, a custom PyTorch dataset, CNN construction, training and evaluation. Device selection supports CUDA, Apple MPS and CPU.

## Repository contents

- `vision/1_hands_on.ipynb`: hands-on classification workflow.
- `vision/0_cnns.ipynb` and `0_cnns.ipynb`: introductory CNN notebooks.

## Running

Use a Python notebook environment with NumPy, PyTorch, torchvision, Pillow, OpenCV, matplotlib and torchinfo. The notebook includes a torchinfo installation cell and downloads the cloud-classification dataset from a Google Cloud Storage URL. Network access is required; GPU acceleration is optional. Run cells in order and inspect the data-loading paths for your environment.

No pinned dependency environment or automated execution check is included. Historical outputs are not a guarantee of reproducibility on a new environment.

## Academic attribution

The hands-on notebook credits **Florient Chouteau** and the [SUPAERO Data Science deep-learning course](https://supaerodatascience.github.io/deep-learning/), and carries a **CC BY-NC-SA 4.0** notice. This repository contains coursework based on those materials; the teaching material and original exercises are not claimed as original work by this account. Preserve the notices when reusing it.

## Status

Coursework snapshot. The notebooks are the primary deliverables; no independently reproduced benchmark is claimed in this README.
