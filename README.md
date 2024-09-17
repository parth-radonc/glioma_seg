# LGG Segmentation on FLAIR MRI Sequences <br />
Autosegmentation of Low Grade Glioma using FLAIR MRI Sequences<br />

# Dataset <br />
  - BRATS(Brain Tumor Segmentation Dataset 2020)
# Models Used - <br />
  1. Baseline UNET <br />
  2. UNET with Squeeze and Excitation <br />
  3. NESTED UNET <br />
  4. U2NET <br />
  5. U2NET with Attention Block <br />
  6. U2NET SMALL <br />
  7. U2NETSMALL+ ATTENTION <br />
  8. PyramidVisionTransformer <br />
  9. Pixeldifferentiation Network on UNet Backbone <br />
  10. Pixeldifferentiation Network on UNet Backbone With Channel + Spatial Attention <br />

# Configuration <br />
  - Optimizer- Adam Optimizer <br />
  - LR - Cosine Annealing LR <br />
  - Loss Fn - BCEDICE LOSS at Multiple Output Layers/scales <br />

# Results <br />
Dice Score = 0.92 <br />

![ Alt text ](https://github.com/parth-radonc/glioma_seg/blob/main/Results/res.jpg?raw=true) 
