# CycleGAN
  An tensorflow Implement of CycleGAN

## Framework
  - Picture below shows the framework of CycleGAN, more details can be seen in this repo.
  
  <p align='center'><img src='./data/a_framework.png'/></p>
  <p align='center'><img src='./data/b_framework.png'/></p>
  
  - Picture below shows the generator, more details can be seen in this repo. 
  
  <p align='center'><img src='./data/a_generator.png'/></p>
  
  - Picture below shows the discriminator, more details can be seen in this repo
  <p align='center'><img src='./data/a_discriminator.png'/></p>
  
  
# Requirement
  
  tensorflow 1.3.0
  
  python 2.7.12
  
  numpy 1.13.1
  
  scipy 0.17.0
  
# Usage
  (1)download this repo to your own directory
  
    $ git clone https://github.com/nnUyi/CycleGAN.git
    $ cd CycleGAN
    
  (2)download [dataset](https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/) and store it in the datasets directory(directory named datasets) and then unzip it. You can use any datasets downloaded from the [website](https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/).
  
  (3)training
    # dataset_name and dataset_dir have the same name, like: horse2zebra
    $ python main.py --is_training=True --dataset_name='*' --dataset_dir='*'
    
  (4)sampling
  
  Sampling process is executed in training time. You can see the sampling results in the directory named sample

# Experiments
  The result shows below, we can clearly obtain such a good experimental result.
  
  |Speckle Noise image|Noise-cancel image|Original image|
  |:-----------------:|:----------------:|:------------:|
  |![Alt test](/images/test/j_1.jpg)|![Alt test](/images/Results/2.png)|![Alt test](/images/real/j_0.jpg)|
  |SNR: 14.16 db<br/>PSNR: 19.63 db<br/>Q-index: 0.9367|SNR: 19.38 db<br/>PSNR: 24.55 db<br/>Q-index: 0.9837||
  |![Alt test](/images/test/k_1.jpg)|![Alt test](/images/Results/3.png)|![Alt test](/images/real/k_0.jpg)|
  |SNR: 15.31 db<br/>PSNR: 21.78 db<br/>Q-index: 0.9308|SNR: 21.95 db<br/>PSNR: 28.42 db<br/>Q-index: 0.9805||

  
  ![Alt test](/data/A_input_1.png) ![Alt test](/data/A_output_1.png)
  ![Alt test](/data/A_input_2.png)![Alt test](/data/A_output_2.png)
  ![Alt test](/data/A_input_3.png)|![Alt test](/data/A_output_3.png)
  
  <p align='center'><img src='./data/a_result.png' /></p>

# Reference

  This repo is finished by referring to [xhujoy/CycleGAN-tensorflow](https://github.com/xhujoy/CycleGAN-tensorflow)
  
# Contacts
  
  Email:computerscienceyyz@163.com, Thank you for contacting if you find something wrong or if you have some problems!!!
