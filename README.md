# medical-image-super-resolution
 
In this project, we use the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for medical image super-resolution.
In our proposed approach, the pre-trained generator and discriminator networks of the 
Real-ESRGAN model are fine-tuned using medical image datasets.

In this project, we worked on retinal images - chest x-ray images. We used the STARE dataset of retinal images and Tuberculosis Chest X-rays (Shenzhen) dataset.
Our fine-tuned model produces more accurate and natural textures, and the output images have better detail and resolution compared to the original real-esrgan model.

datasets can be downloaded from the link below: 

STARE dataset :

https://www.kaggle.com/datasets/vidheeshnacode/stare-dataset

Tuberculosis Chest X-rays (Shenzhen) dataset:

https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xrays-shenzhen

All details and fine-tuning parameters are available in the finetune_realesrgan_x4plus.yml file.

It is also possible to test the original real-esrgan model and fine-tuned model in the fine_tune_retinal_image.ipynb and fine_tune_chest_x_rays.ipynb files

Below are some outputs of the real-esrgan model and the fine-tuned model:

![1](https://user-images.githubusercontent.com/47056654/197423082-6d81adab-e0bc-4cb6-91f3-1bdca78a5f65.jpeg)

![2](https://user-images.githubusercontent.com/47056654/197423096-07b8d15b-c908-4b2d-b1a4-bbd14dcb4090.jpeg)

![3](https://user-images.githubusercontent.com/47056654/197423217-83e54c24-5fef-4c98-b5bf-103e1034ad11.jpeg)

![4](https://user-images.githubusercontent.com/47056654/197423226-e25f6822-ec39-4b12-b223-488d7afabcbe.jpeg)






