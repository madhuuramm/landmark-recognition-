# landmark-recognition-
Project Overview

This project implements a Landmark Recognition system using Deep Learning techniques. It identifies landmarks from images using a pretrained CNN model (MobileNetV2).

 Dataset

Images collected for:

Taj Mahal

Eiffel Tower

Statue of Liberty

Images resized to 224x224

Data split into training (80%) and validation (20%)

 Methodology

Transfer Learning using MobileNetV2

Feature Extraction using CNN

Softmax classifier for multi-class classification

 Steps to Run

Install dependencies

Place dataset in dataset/ folder

Train model:

python train.py

Test model:

python predict.py
 Results

Model Accuracy: ~85–95% (depends on dataset)

Correctly identifies landmarks from test images

 Challenges

Limited dataset size

Similar-looking landmarks

 Improvements

Use larger datasets (Google Landmark Dataset)

Fine-tune model

Deploy as web app

 8. Output Example
Predicted Landmark: taj_mahal
