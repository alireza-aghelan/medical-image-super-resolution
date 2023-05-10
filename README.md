# medical-image-super-resolution
 
In this work, we modify the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for medical image super-resolution.
In our proposed approach, the pre-trained generator and discriminator networks of the Real-ESRGAN model are fine-tuned using medical image datasets. 

In this project, we worked on chest X-ray and retinal images. We use the STARE dataset of retinal images and the Tuberculosis chest X-rays (Shenzhen) dataset for fine-tuning.

The download links of chest X-ray and retinal datasets:

STARE dataset:

https://www.kaggle.com/datasets/vidheeshnacode/stare-dataset

Tuberculosis Chest X-rays (Shenzhen) dataset: 

https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Results for chest x-ray and retinal images are shown in the following figures.

# Retinal images 

![1](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/859537c8-2f8e-44b0-bec4-e5452299a66e)

Columns 1–4 are degraded LR images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images. 

![2](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/0ff3d613-5b36-4ec4-984f-ce7050143688)

# Chest X-ray images 

![3](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/168e1c37-6694-4e7d-93e9-a2778fb66f1f)

Columns 1–4 are degraded LR images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and ground truth HR images. 

![4](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/a76529ef-bd65-4fbc-ab19-c03d6e8b0b27)

