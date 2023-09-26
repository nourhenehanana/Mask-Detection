# Mask-detection
The "Mask-Detection" repository is a deep learning project focused on real-time mask detection using pre-trained MobileNetV2 as a base model for transfer learning. Below is a more detailed description of the project:

# 1. Project Overview:

The project aims to develop a deep learning model for real-time mask detection in images or videos.
Transfer learning is employed, using a pre-trained MobileNetV2 model as the base architecture.
The last layers of the MobileNetV2 model are modified to perform binary classification (mask present or absent).
# 2. Dataset:

A labeled dataset from Kaggle is used, consisting of 2994 images of people wearing masks and 2994 images of people not wearing masks.
The dataset is split into training and validation sets for model training and evaluation.
# 3. Model Accuracy:

The model achieves impressive accuracy results:
Training Set Accuracy: 0.96 (96%)
Validation Set Accuracy: 0.90 (90%)
These accuracy metrics indicate that the model performs well in both training and validation, suggesting that it has learned to differentiate between masked and unmasked individuals effectively.
![plot](https://github.com/nourhenehanana/Mask-Detection/assets/93352403/d17d1e45-13bb-43c5-a9c9-9addda4e0f01)
# 4. Model Architecture:

The MobileNetV2 architecture is used as the backbone for feature extraction.
The final layers of the MobileNetV2 model are modified to include a custom classification head for mask detection.
# 5. Real-Time Testing:

The trained model is saved and can be tested in real time using OpenCV.
The "detect_mask_video" script allows users to use their webcam or input video streams to detect the presence or absence of masks on individuals.
![git1](https://github.com/nourhenehanana/Mask-Detection/assets/93352403/92b4751c-3927-4f80-a337-10b527816d7f)
