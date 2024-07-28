# Medical image super-resolution
 
Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) is a powerful model that has shown remarkable performance in recovering high-resolution (HR) images from real-world low-resolution (LR) images. In this work, we fine-tune the pre-trained Real-ESRGAN model for medical image super-resolution. We use the STARE dataset and the Tuberculosis chest X-rays (Shenzhen) dataset for fine-tuning. The fine-tuned model can better preserve fine details and produce more realistic images. 

Below are the download links of chest X-ray and retinal datasets.

Tuberculosis chest X-rays (Shenzhen) dataset: 

https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen

STARE dataset:

https://www.kaggle.com/datasets/vidheeshnacode/stare-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

The results are shown in the following Figures.

## Retinal images
### Retinal images

![1](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/961af6a5-d667-470d-9d0e-cc83ce074082)

Results for images of the DRIVE dataset. Columns 1–4 are degraded LR images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images.

![2](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/0c40e5c3-3039-455d-8ff5-a5ee2307373d)

Magnified regions of a retinal image. (a) Degraded LR image. (b) Real-ESRGAN output. (c) Fine-tuned Real-ESRGAN output. (d) Ground truth HR image.

# Chest X-ray images

![3](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/5a79d6fc-7771-4e99-8fbb-ba63d35cb4dc)

Results for images of the NIH chest X-ray dataset. Columns 1–4 are degraded LR images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images.

![4](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/84591627-497a-462f-b83b-e2e138302a94)

Magnified regions of a chest X-ray image. (a) Degraded LR image. (b) Real-ESRGAN output. (c) Fine-tuned Real-ESRGAN output. (d) Ground truth HR image.
