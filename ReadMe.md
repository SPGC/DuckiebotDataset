# Dataset for duckiebot

Here you can find dataset for road markup detection on duckiebot

Dataset is still in developing

## What have been done
1. Created 8480 images with road markup (data folder)
2. Created pixel mask for each image  (labels folder)
3. Created combined image with raw image and pixel mask for better evaluation (data_and_labels folder)

## Warnings
1. There is no red stop lines in this dataset (probably will be added later)
2. Pixel maps are noisy

## Contribution
You can help me in improving this dataset by:
1. Making better pixel maps (remove noise)
2. Adding more images with pixel maps
3. Adding images with red stop lines 

## Creating dataset
Dataset was created with using EM algorithm for generating pixel maps after that each map was revised by human

