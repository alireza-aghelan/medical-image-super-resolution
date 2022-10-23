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

![2](https://user-images.githubusercontent.com/47056654/197424054-8b85a259-48e4-42a8-a115-2b52d7c0533e.jpeg)

![3](https://user-images.githubusercontent.com/47056654/197424062-bef85a5c-0fe3-454c-b29d-5b752fc84a73.jpeg)

![4](https://user-images.githubusercontent.com/47056654/197424112-6921705e-8106-47dd-8bf1-9ab7b6c349b7.jpeg)

![5](https://user-images.githubusercontent.com/47056654/197424125-9fa031e0-ec38-499d-8965-d3d8b1f7bb27.jpeg)

![6](https://user-images.githubusercontent.com/47056654/197424134-70f44af0-168d-49c9-81e2-885cce8fab57.jpeg)












