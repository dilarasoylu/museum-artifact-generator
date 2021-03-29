# Museum Artifact Generator

Museum Artifact Generator is a GAN model that can generate museum artifacts given a text description. If you would like to run the DCGAN model, follow the instructions in the `code_dcgan/Network - Generating Museum Objects` notebook. If you would like to run the FastGAN model, navigate to the `code_fastgan` folder, install the requirements and run:

`python train.py --path ../data/train/ --im_size 256 --batch_size 32 --iter 12500`

You can replace the hyperparameters as you wish. 

## Resources

The `code_fastgan` folder in this repository is a modified version of this repository: https://github.com/odegeasslbc/FastGAN-pytorch. 
