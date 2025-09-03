# Landslide Detection from Satellite Imagery
## Project Overview
This project uses a deep learning model to perform semantic segmentation on satellite imagery to detect and map landslides. By training on multi-modal remote sensing data, the model learns to identify the unique signatures of landslide areas, providing a critical tool for disaster monitoring, risk assessment, and emergency response.

The model is built using the TensorFlow and Keras frameworks and leverages a U-Net-like architecture, which is highly effective for image segmentation tasks. A custom dice loss function is implemented to handle the class imbalance often present in this type of geospatial data.

## Dataset: Landslide4Sense
This project utilizes the Landslide4Sense benchmark dataset, a comprehensive collection of multi-sensor satellite images designed specifically for landslide detection research.

The dataset includes 14 data bands for each image patch, including:
1. Multispectral data from Sentinel-2
2. Slope data from ALOS PALSAR
3. Digital Elevation Model (DEM) from ALOS PALSAR

## Where to Download
The dataset is publicly available and can be downloaded from multiple sources. The official competition link on Zenodo is recommended:

Download from [Zenodo](https://zenodo.org/records/10463239)

You can also find it on [Kaggle](https://www.kaggle.com/datasets/tekbahadurkshetri/landslide4sense).
