# medical-image-super-resolution
 
In this work, we modify the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for medical image super-resolution.
In our proposed approach, the pre-trained generator and discriminator networks of the Real-ESRGAN model are fine-tuned using medical image datasets. 

In this project, we worked on chest X-ray and retinal images and used the STARE dataset of retinal images and Tuberculosis Chest X-rays (Shenzhen) dataset for fine-tuning. The proposed model produces more accurate and realistic textures, and its outputs have more realistic details compared to the original Real-ESRGAN outputs.

datasets can be downloaded from the link below: 

STARE dataset :

https://www.kaggle.com/datasets/vidheeshnacode/stare-dataset

Tuberculosis Chest X-rays (Shenzhen) dataset:

https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Results of chest x-ray and retinal images:

# Retinal images 

![1](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/90607bee-b4b5-49f4-ae76-c508fab100c5)
![2](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/c6e6ec6f-709e-416a-8007-55f2fafac91f)


# Chest X-ray images 

![1](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/88bd201d-8497-458f-8555-c6d64db52093)
![2](https://github.com/alireza-aghelan/medical-image-super-resolution/assets/47056654/3a823219-cab3-4c37-8909-0ab58b6ed951)
