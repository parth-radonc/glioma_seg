# glioma_seg
# LGG Segmentation on FLAIR MRI Sequences
Autosegmentation of Low Grade Glioma using FLAIR MRI Sequences

#Dataset - BRATS
#Models Used -
Baseline UNET
UNET with Squeeze and Excitation
NESTED UNET
U2NET
U2NET with Attention Block
U2NET SMALL
U2NETSMALL+ ATTENTION
PyramidVisionTransformer
Pixeldifferentiation Network on UNet Backbone
Pixeldifferentiation Network on UNet Backbone With Channel + Spatial Attention

# Configuration
Optimizer- Adam Optimizer
LR - Cosine Annealing LR
Loss Fn - BCEDICE LOSS at Multiple Output Layers/scales

# Results
Dice Score = 0.92

![ Alt text(https://github.com/parth-radonc/glioma_seg/blob/main/Results/res.jpg) 
