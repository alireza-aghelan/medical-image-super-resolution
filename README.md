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

![1](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/4ee53819-014c-42c8-b9cd-dd4546f21ad2)

Columns 1–4 are degraded LR images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images.

![2](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/f85cf4f7-9f76-49f1-901a-9fb7e0063255)

# Chest X-ray images 

![3](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/b564c090-f950-4fb5-bac9-340fe4042408)

Columns 1–4 are degraded LR images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images. 

![4](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/f29f1dea-694a-428a-a3ec-31c481ff9315)

