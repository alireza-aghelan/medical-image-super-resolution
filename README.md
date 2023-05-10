# medical-image-super-resolution
 
In this work, we modify the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for medical image super-resolution. We work on chest X-ray and retinal images. In the proposed approach, the pre-trained Real-ESRGAN model is fine-tuned separately on chest X-ray and retinal datasets. We use the STARE dataset and the Tuberculosis chest X-rays (Shenzhen) dataset for fine-tuning. The fine-tuned model can better preserve fine details and produce more realistic images. 

Below are the download links of chest X-ray and retinal datasets.

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

