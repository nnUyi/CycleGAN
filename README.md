# CycleGAN
  An tensorflow Implement of CycleGAN

## Framework
  - Picture below shows the framework of CycleGAN, more details can be seen in this repo.
  
  <p align='center'><img src='a_framework.png'/></p>
  <p align='center'><img src='b_framework.png'/></p>
  
  - Picture below shows the generator, more details can be seen in this repo. 
  
  <p align='center'><img src='a_generator.png'/></p>
  
  - Picture below shows the discriminator, more details can be seen in this repo
  <p align='center'><img src='a_discriminator.png'/></p>
  
  
# Requirement
  
  tensorflow 1.3.0
  
  python 2.7.12
  
  numpy 1.13.1
  
  scipy 0.17.0
  
# Usage
  (1)download this repo to your own directory
  
    $ git clone https://github.com/nnUyi/CycleGAN.git
    
  (2)download celebA dataset and store it in the datasets directory(directory named datasets, sub-directory name celebA), in this repo, I just use the face images with no attributes. Input is the original images without any cropping operation, then it will be cropped into given resolution in this repo.
  
  (3)training
  
    $ python main.py --is_training=True
    
  (4)sampling
    
    Sampling process is executed in training time. You can see the sampling results in the directory named sample

# Experiments
  The result shows below, after 15 epoches, we can clearly obtain such a good experimental result.
  
  <p align='center'><img src='a_train_15_0000.png' /></p>

# Reference

  This repo is finished by referring to [naturomics-CapsNet-Tensorflow](https://github.com/naturomics/CapsNet-Tensorflow/issues)
# Contacts
  
  Email:computerscienceyyz@163.com, Thank you for contacting if you find something wrong or if you have some problems!!!

