---
title: ResNET CNN for Heart Disease Classification
summary: A Convolutional Neural Network (CNN) pipeline for the prediction of heart conduction disorders (CD) using ECGs data.
tags:
  - ML Stats
date: '2023-05-30'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
 
---
I recently completed a machine learning project detecting heart conduction disorders from electrocardiogram (ECG) data. These types of problems can lead to sudden cardiac death, so early detection through screening is critical.

My team and I tested several techniques on an open dataset of over 20,000 ECGs. Simple approaches like auto-encoders failed to capture nuances in the waveforms. Extracting pre-defined features improved results but required specialized medical knowledge. Ultimately, convolutional neural networks (CNNs) performed the best by learning subtle patterns on their own.

Our final multi-scale ResNet CNN achieved an AUC score of 0.885. This means it reliably distinguishes normal ECGs from those with conduction abnormalities. In an external validation on real patient data, it maintained strong performance.

The model takes advantage of CNN architectural elements like residual connections and filters at multiple scales to hierarchically extract both local and global patterns. This level of nuanced feature extraction exceeds human perception limitations.

![model](model-archetecture.jpg)

The codes and detailed documents can be retrieved via my [GitHub Repo](https://github.com/YaxuanSeanZhang/ResNet-CNN-ECG).

