# Medical image super-resolution
 
In this work, we fine-tune the pre-trained Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model to improve the resolution and quality of chest X-ray and retinal images. We use the STARE dataset and the Tuberculosis chest X-rays (Shenzhen) dataset for fine-tuning. The fine-tuned model can better preserve fine details and produce more realistic images. 

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

![2](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/2a933cb4-1682-4a16-a7c1-f439f265b053)

# Chest X-ray images 

![3](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/b564c090-f950-4fb5-bac9-340fe4042408)

Columns 1–4 are degraded LR images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images. 

![4](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/c58e4e19-fb21-4dc5-afc5-2f243a288911)
