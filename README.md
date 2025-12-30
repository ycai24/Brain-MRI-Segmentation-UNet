# Brain Tumor Segmentation using U-Net

## Project Overview
This project implements a Deep Learning model (U-Net) to automatically detect and segment brain tumors from MRI scans. It uses PyTorch to process the LGG Segmentation Dataset.

## Key Features
* **Architecture:** U-Net with Skip Connections.
* **Loss Function:** Dice Loss (optimized for medical image segmentation).
* **Data Processing:** Custom PyTorch Dataset loader with OpenCV for image normalization.

## Results
The model successfully localizes tumor regions. Below is a sample prediction (Right) compared to the Ground Truth (Center).

![Model Results](result_sample.png)

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt