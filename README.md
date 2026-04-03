# Fine-tuned Generative Adversarial Network-based Model for Medical Image Super-Resolution

[**Paper (IEEE)**](https://ieeexplore.ieee.org/abstract/document/10874705) | [**Paper (arXiv Preprint)**](https://arxiv.org/abs/2211.00577)

**Alireza Aghelan**, **Modjtaba Rouhani**

## Overview
This repository presents the implementation of our paper, **Fine-tuned Generative Adversarial Network-based Model for Medical Image Super-Resolution**.

In this work, we adapt the pre-trained **Real-ESRGAN** model to the medical imaging domain through **transfer learning**. The goal is to enhance the resolution and perceptual quality of medical images while preserving diagnostically important fine details. 

Compared with the original Real-ESRGAN baseline, the fine-tuned model produces improved perceptual quality, better detail preservation, and more realistic textures in reconstructed medical images.

The datasets used for training the proposed model are listed below.

- **Tuberculosis Chest X-ray (Shenzhen):** [Dataset Link](https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen)
- **STARE (Retinal Images):** [Dataset Link](https://www.kaggle.com/datasets/vidheeshnacode/stare-dataset)

The Real-ESRGAN code is borrowed from [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN).

The results are shown in the following Figures.

# Retinal images

![1](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/961af6a5-d667-470d-9d0e-cc83ce074082)

Results for images of the DRIVE dataset. Columns 1–4 are degraded LR images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images.

---

![2](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/0c40e5c3-3039-455d-8ff5-a5ee2307373d)

Magnified regions of a retinal image. (a) Degraded LR image. (b) Real-ESRGAN output. (c) Fine-tuned Real-ESRGAN output. (d) Ground truth HR image.

# Chest X-ray images

![3](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/5a79d6fc-7771-4e99-8fbb-ba63d35cb4dc)

Results for images of the NIH chest X-ray dataset. Columns 1–4 are degraded LR images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images.

---

![4](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/84591627-497a-462f-b83b-e2e138302a94)

Magnified regions of a chest X-ray image. (a) Degraded LR image. (b) Real-ESRGAN output. (c) Fine-tuned Real-ESRGAN output. (d) Ground truth HR image.
