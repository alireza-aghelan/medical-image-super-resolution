# Medical image super-resolution
 
Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) is a powerful model that has shown remarkable performance in recovering high-resolution (HR) images from real-world low-resolution (LR) images. In this work, we fine-tune the pre-trained Real-ESRGAN model for medical image super-resolution. We use the STARE dataset and the Tuberculosis chest X-rays (Shenzhen) dataset for fine-tuning. The fine-tuned model can better preserve fine details and produce more realistic images. 

Below are the download links of chest X-ray and retinal datasets.

Tuberculosis chest X-rays (Shenzhen) dataset: 

https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen

STARE dataset:

https://www.kaggle.com/datasets/vidheeshnacode/stare-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Results for chest x-ray and retinal images are shown in the following figures.

# Retinal images 

![1](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/311f5c9b-73c9-4347-a30f-0f93e240f5e0)

Columns 1–4 are degraded LR images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images.

![2](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/7b453caf-b63b-4974-83d2-b7bcf0451262)

# Chest X-ray images 

![3](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/9413c246-8640-419d-b181-489e4e7c03a2)

Columns 1–4 are degraded LR images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images. 

![4](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/9faa84b6-bf68-4221-8363-f6cd2357d999)
