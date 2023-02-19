# GAN_Flower_TF_Dataset
This project aims to teach GAN model with Python language and Tensorflow library 
Here we using TF-Flower dataset from:
https://www.tensorflow.org/datasets/catalog/tf_flowers

After downloading data and prepare, we use some preprocess like resize and normalization.

Then using data augmentation tools to produce larger dataset.

Next step is creating the Generator and discriminator, the structure of both was explain in script.

It is necessary to mention that for faster training, the photos were resized to 64 x 64 pixels, and for this reason, the output estimates are blurred, and in the initial implementation, which took a lot of time, these results are very accurate and was on 680 x 680 pixel. Unfortunately, the first output crashed and was lost and could not be saved, so lower pixels were produce to get the output faster.

