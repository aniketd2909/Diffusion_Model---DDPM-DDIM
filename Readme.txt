# Diffusion Model using Denoising Diffusion Probabilistic Models (DDPM) and Denoising Diffusion Implicit Models (DDIM)
## Included Inferencing using Frechet Inception Distance score (FID)
## Model is trained on 89400 sprite images, (16X16X3) dimensions
## Performed 200 epochs
## Used DDPM, DDIM models for sampling and showed the differences
## Plotted models at interval of 40,80,120,199
## Saved 15 output images from each model
## Used those 15 ouput images of each model and 200 input images and calculated the FID score for each model

## The Code is self explanatory

Steps Involved:

1) Installing the required modules
2) Loading the input dataset
3) Training
4) Saving model at intervals of 20 epochs
5) Using the trained model with sampling process - DDIM to plot the images
6) Saved 15 ouptut images for each model i.e 40,80,120,199 epochs
7) Calculated the FID scores for each model






Credits

- https://learn.deeplearning.ai/diffusion-models/
- https://github.com/Ryota-Kawamura/How-Diffusion-Models-Work
