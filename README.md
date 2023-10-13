# Flood Area Segmentation with Deep Learning

## Introduction

This project presents a flood area segmentation application using SOTA deep learning models, including UNet and DeepLabV3. The application processes satellite and aerial images, identifying and highlighting flood-affected regions with high precision. By leveraging these models, I have achieved DICE scores of 0.82 with UNet and 0.86 with DeepLabV3.

## Features

- **Semantic Segmentation:** Utilizes deep learning models (UNet and DeepLabV3) for precise semantic segmentation of flood-affected regions.
- **Satellite and Aerial Image Support:** Process both satellite and aerial images to identify flood-affected areas.
- **High Precision:** Achieved high DICE scores (0.82 with UNet, 0.86 with DeepLabV3) to ensure accurate flood area identification.
- **Easy-to-Use:** User-friendly interface for users to perform flood area segmentation on their own datasets.
- **Customization:** Flexible parameters and model choices for users to fine-tune the segmentation process.
- **Open Source:** This project is open source, allowing for contributions from the community to further improve flood area segmentation.

## Installation

To install and run the flood area segmentation application, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/roadrollerdafjorst/flood-area-segmentation.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Change directory to src.

   ```bash
   cd src
   ```

5. Run the application:

    ```bash
    python app.py
    ```

## Usage

1. Launch the application as described in the installation section.

2. Upload the satellite or aerial image you want to process.

3. Choose the segmentation model (UNet or DeepLabV3) and set the required parameters.

4. Click the "Segment" button to start the flood area segmentation process.

5. The segmented image will be displayed, with flood-affected regions highlighted.

6. You can save the segmented image or further analyze the results as needed.

## Results

The deep learning models utilized in this project have produced impressive results:

- UNet: DICE Score of 0.82
- DeepLabV3: DICE Score of 0.86
