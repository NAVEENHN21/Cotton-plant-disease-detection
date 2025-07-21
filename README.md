# Cotton Plant Disease Detection Using Deep Learning

This repository documents a deep learning-based project aimed at detecting and classifying cotton plant diseases from leaf images. The project was developed as part of the final year engineering curriculum at Vidyavardhaka College of Engineering, Mysuru.

## Project Overview

Cotton is a vital cash crop in India, but its productivity is often affected by various leaf diseases. This project proposes a solution using Convolutional Neural Networks (CNNs) to accurately identify diseases from cotton leaf images and suggest appropriate cures.

The system is designed to:
- Detect and classify diseases from images (live or uploaded).
- Suggest appropriate chemical and organic cures.
- Display insights on cotton production trends and trading factors.

## Key Features

- Image-based disease detection using CNN
- 95%+ model accuracy
- Identifies five categories:
  - Leaf Lesions
  - Bacterial Blight
  - Curl Virus
  - Fusarium Wilt
  - Healthy
- Treatment suggestions (chemical and organic)
- Android app interface with live camera support
- Production forecast of cotton in bales (ARIMA model)
- Details about major cotton varieties in India

## Model Architecture

The system uses a Convolutional Neural Network (CNN) with the following pipeline:
1. Image Input (Live/Upload)
2. Preprocessing (Noise reduction, Resizing)
3. Feature Extraction (Convolution + Pooling layers)
4. Classification (Fully connected layers + Softmax)
5. Prediction and Cure Display

## Tech Stack

- Language: Python, Kotlin
- Libraries: TensorFlow, Keras, NumPy, Flask
- Tools: Jupyter Notebook, Android Studio, VS Code
- Dataset: 2500+ images from Kaggle and field collection


## Performance

| Model/Method          | Accuracy   |
|-----------------------|------------|
| CNN (Proposed)        | 95.00%     |
| SVM                   | 91.00%     |
| GA-SVM                | 90.00%     |
| K-Means               | 86.00%     |
| Pattern Recognition   | 85.52%     |

## Future Scope

- Real-time detection using IoT-enabled devices
- Integration with environmental sensors (humidity, temperature)
- Mobile-based offline model inference
- Multi-crop disease detection support
- Larger, more diverse datasets


