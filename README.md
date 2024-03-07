# DeepToon: Cartoonization of Reality using Deep Learning

In this work, we investigate two different architectures: styleGAN and animeGAN, the latter being particularly noteworthy as a new and lightweight generative adversarial network designed 
for fast animation style transfers. Our experiments show that animeGAN outperforms styleGAN in producing high-quality images. Test findings demonstrate that it can quickly 
convert real-world photos into high-quality anime representations, both in a new dataset and in comparison to baseline datasets.

# Implementation details:

We utilized the implementations of the following kaggle and github reco in our cases. For detailed implementation please follow the guidelines of the following links:

1. https://www.kaggle.com/code/dunky11/stylegan
2. https://github.com/TachibanaYoshino/AnimeGAN
3. https://github.com/ptran1203/pytorch-animeGAN/tree/master


# Dataset we used in our works:

We used the following datasets in our project:

1. https://www.kaggle.com/datasets/arnaud58/selfie2anime/data
2. https://www.kaggle.com/datasets/insaiyancvk/dragon-ball-z-dataset
3. J. Chen, G. Liu, and X. Chen. AnimeGAN: a novel lightweight gan for photo animation. In International symposium on intelligence computation and applications, pages 242–256. Springer, 2020

# Detailed Implementation:

For Colab User: You don't need any packages to install to work with the colabs. You could directly follow the guidelines provided in the notebook files. Be sure that your drive is properly mounted and all the data are
in appropriate structure.

For user in the server end:

Before implementation you need to install all the appropriate package provided in the requirements.txt function.

Steps:

1. Change the extension of the provided requirements.txt file to .yml.
2. write the following command in the command prompt: conda env create --name my_env --file=requirements.yml \\
   
   Make sure you have anaconda or miniconda installed in your server.
   A detailed step by step installation process you can find in the following website:
   https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html
3. Activate the environment by running: conda activate my_env
4. Follow the step by step process provided in the notebook files.
   
