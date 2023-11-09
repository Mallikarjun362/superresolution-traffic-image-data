# Super Resolution of Traffic Image Data

## Datasets Used :

1. [Traffic vehicles Object Detection](https://www.kaggle.com/datasets/hasibullahaman/objectdetectiondatasetcar) **(Main)**
2. [Traffic vehicles Object Detection](https://www.kaggle.com/datasets/saumyapatel/traffic-vehicles-object-detection)
3. [Traffic Detection Project](https://www.kaggle.com/datasets/yusufberksardoan/traffic-detection-project)

## Referanced Blog Articles:

- [Super Resolution — A Basic study](https://towardsdatascience.com/super-resolution-a-basic-study-e01af1449e13)

## Data Pre-Processing:

- Dataset: [Traffic vehicles Object Detection](https://www.kaggle.com/datasets/hasibullahaman/objectdetectiondatasetcar) (Source : Kaggle).
- The entire input is trained through the establishment of two data loaders train_loader (80% data) and val_loader (20% data).
- The input pipeline consists of 4X downscaling the High-resolution traffic images.

## Data Pipeline:

- Implementing SRGAN architecture consisting of a Generator and Discriminator as the base model
- Training generator with Discriminator loss, VGG loss, MSE loss, TV loss.

## Results:

- PSNR and SSIM are the two main metrics used to measure performance.
- PSNR: 22.4812 and SSIM: 0.7031 (max 1).
- Our main metric is through visual analysis.

## Final Deliverables:

- A Robust Generative Adversarial model to upscale the traffic images. **(Model)**
- Training and testing pipeline code. **(Code)**

# Group Members

## Perumallu Mallikarjun (12041030)

## Mohammad Sameer (12040890)
