# Chest X-Ray Opacity Detection

Notebooks used to train and evaluate PyTorch 2D Object detection models from the summer of 2021. 5-Fold cross validation was used on Chest X-Rays from the SIIM FISABIO RSNA COVID-19 dataset. The models output bounding boxes around the opacities in the lungs. The image below shows sample outputs, keeping only predictions with above 60% confidence.

![image](https://user-images.githubusercontent.com/69114450/147623539-fc0d8851-f09a-485d-b5cf-7b07c74ccc36.png)
