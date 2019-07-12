# Emoji conversion algorithm
Deep learning model to convert apple emojis to microsoft emojis and vice versa 

## Usage:

    To train with the default hyperparamters (saves results to samples_cyclegan/):
       python cycle_gan.py

    To train with cycle consistency loss (saves results to samples_cyclegan_cycle/):
       python cycle_gan.py --use_cycle_consistency_loss
## Prerequisites:
    Numpy
    Scipy
    Pytorch
