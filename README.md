# License Plate Detection System

This GitHub repository contains version 1 code for a License Plate Detection system using deep learning with TensorFlow and OpenCV. The system detects license plates in images, segments the characters on the plate, and predicts the characters to recognize the license plate number.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setting Up](#settingup)
- [How To Use](#usage)
- [Results](#results)

## Introduction

This repository provides a detailed guide on setting up and effectively using the License Plate Number Recognition system. If you're passionate about AI-driven solutions and looking to detect license plate numbers, you're in the right place!

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- TensorFlow
- OpenCV
- NumPy
- Matplotlib
- Any necessary dependencies mentioned in the code.

## Setting Up

1. Begin by cloning this repository to your desired location:

```bash
git clone https://github.com/AnimeshR22/License-Plate-Number-Recognition.git

```

2. Install the required Python packages using pip.

```bash
pip install tensorflow opencv-python numpy matplotlib
```

## How To Use

1. Place your license plate images in the appropriate directories. Images for training should be placed in `Train_Character/train`, and validation images should be placed in `Train_Character/val`.

2. To train the model, run the provided code by executing the script `train_model.py`. The model will be trained to recognize characters on license plates.

```bash
python train_model.py
```

3. To recognize license plates in an image, run the script `recognize_license_plate.py`. This script loads the trained model, detects license plates, segments characters, and predicts the license plate number.

```bash
python main.py
```

4. The recognized license plate number will be displayed and saved as an output image.

## Results

The License Plate Detection system provides the following results:

- Detection of license plates in input images.
- Segmentation of characters on the license plate.
- Prediction of the characters to recognize the license plate number.
- Display of the recognized license plate and saving it as an output image.

![Input Image](input_image.png)

![Output Image](output_image.png)

