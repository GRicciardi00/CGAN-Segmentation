#Image-to-Image Translation with Conditional GAN (cGAN)
## Overview
This project focuses on the implementation of a Conditional Generative Adversarial Network (cGAN) for image-to-image translation, specifically targeting the generation of realistic segmented images from input images.<br/>
The primary objective is to make image segmentation more accessible while providing valuable experience in utilizing cGANs.

## Dataset
The project uses a subset of the Cityscapes dataset, a widely used dataset for semantic segmentation.

## Evaluation
For evaluation, pixel-wise accuracy is used to measure the percentage of correctly classified pixels in the generated segmentation compared to the ground truth. This metric provides insights into the model's performance on the validation set.

## U-Net Comparison
In addition to the cGAN, a U-Net model is implemented and trained for comparison. The U-Net architecture, known for its effectiveness in image segmentation, is used to assess the cGAN's performance. <br/>
The project compares the results of the cGAN and U-Net models, providing insights into their respective strengths and weaknesses. <br/>
Pixel-wise accuracy on the validation set is calculated to quantify the performance of both models.

## Results
Di seguito vengono mostrate le immagini generate dopo 50 epoche sul training set dal 
- CGAN
![U-Net result](https://github.com/GRicciardi00/CGAN-Segmentation/blob/main/CGAN%20result.png)
- U-Net
![U-Net result](https://github.com/GRicciardi00/CGAN-Segmentation/blob/main/U-Net%20result.png)
