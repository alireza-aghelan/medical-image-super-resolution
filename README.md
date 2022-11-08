# medical-image-super-resolution
 
In this project, we use the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for medical image super-resolution.
In our proposed approach, the pre-trained generator and discriminator networks of the 
Real-ESRGAN model are fine-tuned using medical image datasets.

In this project, we worked on retinal images - chest X-ray images. We used the STARE dataset of retinal images and Tuberculosis Chest X-rays (Shenzhen) dataset.
Our fine-tuned model produces more accurate and natural textures, and the output images have better detail and resolution compared to the original real-esrgan model.

datasets can be downloaded from the link below: 

STARE dataset :

https://www.kaggle.com/datasets/vidheeshnacode/stare-dataset

Tuberculosis Chest X-rays (Shenzhen) dataset:

https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen

All details and fine-tuning parameters are available in the finetune_realesrgan_x4plus.yml file.

It is also possible to test the original real-esrgan model and fine-tuned model in the fine_tune_retinal.ipynb and fine_tune_chest_x_rays.ipynb files.

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Below are some outputs of the real-esrgan model and the fine-tuned model:

Columns 1–4 are the high-resolution ground truth images, LR degraded images, the outputs of the original Real-ESRGAN, and the outputs of the fine-tuned Real-ESRGAN.

# Retinal images 

![1](https://user-images.githubusercontent.com/47056654/200589674-4bf4dfff-4ea5-4ba0-a76e-d02d30359fcc.jpeg)

![2](https://user-images.githubusercontent.com/47056654/200147608-a1ea47b6-8960-4b3d-adc3-16a4cb84c80f.jpeg)


# Chest X-ray images 

![5](https://user-images.githubusercontent.com/47056654/200582048-c2651ff4-e743-48e4-acd1-dcde04a1c9b1.jpeg)

![6](https://user-images.githubusercontent.com/47056654/200175085-c7a77fd5-0b04-4437-9b0d-213522bba052.jpeg)



