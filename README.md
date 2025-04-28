## Description of the problem and data

This project is based on the Kaggle Histopathologic Cancer Detection competition. The goal is to look at small square pictures (96x96 pixels) from pathology scans and decide if the very center (32x32 pixels) of the picture contains cancer tissue. It's a binary classification problem: label 1 means cancer is present in the center, label 0 means it's not.

The full training dataset has about 220,000 images, which is quite large. Each image is 96x96 pixels with 3 color channels (RGB). For this project, to make things faster, I'll use a smaller random sample (subset = 30k imgs) of the training data.
