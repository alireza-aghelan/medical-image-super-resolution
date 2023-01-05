# medical-image-super-resolution
 
In this work, we modify the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for medical image super-resolution.
In our proposed approach, the pre-trained generator and discriminator networks of the Real-ESRGAN model are fine-tuned using medical image datasets. 

In this project, we worked on chest X-ray and retinal images and used the STARE dataset of retinal images and Tuberculosis Chest X-rays (Shenzhen) dataset for fine-tuning. The proposed model produces more accurate and realistic textures, and its outputs have more realistic details compared to the original Real-ESRGAN outputs.

datasets can be downloaded from the link below: 

STARE dataset :

https://www.kaggle.com/datasets/vidheeshnacode/stare-dataset

Tuberculosis Chest X-rays (Shenzhen) dataset:

https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen

All details and fine-tuning parameters are available in the finetune_realesrgan_x4plus.yml file.

It is also possible to test the original real-esrgan model and fine-tuned model in the fine_tune_retinal.ipynb and fine_tune_chest_x_rays.ipynb files.

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Below are some outputs of the real-esrgan model and the fine-tuned model:

# Retinal images 

![1](https://user-images.githubusercontent.com/47056654/200589674-4bf4dfff-4ea5-4ba0-a76e-d02d30359fcc.jpeg)

Columns 1–4 are HR ground truth images, LR degraded images, original Real-ESRGAN outputs, and fine-tuned Real-ESRGAN outputs.

![2](https://user-images.githubusercontent.com/47056654/200147608-a1ea47b6-8960-4b3d-adc3-16a4cb84c80f.jpeg)

# Chest X-ray images 

![3](https://user-images.githubusercontent.com/47056654/201715742-f6ed3780-bf96-4802-b73d-5620bd181911.jpeg)

Columns 1–4 are HR ground truth images, LR degraded images, original Real-ESRGAN outputs, and fine-tuned Real-ESRGAN outputs. 

![4](https://user-images.githubusercontent.com/47056654/201715833-3d3ec3cb-b805-4545-9ba2-5980df4b4a52.jpeg)
