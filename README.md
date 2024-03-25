# ComfyUI-BiRefNet

## Introduction

The Bilateral Reference Network (BiRefNet) achieves state-of-the-art results in multiple Salient Object Segmentation datasets. This repository integrates BiRefNet as ComfyUI nodes, simplifying access to this advanced model.

## Installation

Install the BiRefNet node in your ComfyUI environment:

1. Navigate to your ComfyUI custom nodes directory:
   ```bash
   cd ComfyUI/custom_nodes/
   ```
2. Clone the BiRefNet repository:
   ```bash
   git clone https://github.com/viperyl/ComfyUI-BiRefNet.git
   ```
3. Install the necessary requirements:
   ```bash
   pip install -r ComfyUI-BiRefNet/requirements.txt
   ```

## Model Checkpoints

Before using BiRefNet, download the model checkpoints with Git LFS:

1. Ensure `git lfs` is installed. If not, [install it](https://git-lfs.github.com/).
2. Download the checkpoints to the ComfyUI models directory:
   ```bash
   cd ComfyUI/models/
   git clone https://huggingface.co/ViperYX/BiRefNet
   cd BiRefNet
   git lfs install
   git lfs pull
   ```

## Usage

The demo workflow placed in `workflow/example_workflow.json`

![plot](./assets/Screenshot-2024-03-21-at-19.26.21.png)

## Sample Result

![](./assets/00.jpg)

![](./assets/01.jpg)

![](./assets/02.jpg)

# Acknowledgments

Thanks to BiRefNet repo owner [ZhengPeng7/BiRefNet: Bilateral Reference for High-Resolution Dichotomous Image Segmentation (github.com)](https://github.com/zhengpeng7/birefnet)

