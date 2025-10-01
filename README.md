
# Animal Subspecies Classification

This project focuses on the classification of animal subspecies using machine learning models. The models trained in this repository are designed to classify images of animals into various subspecies categories.

## Table of Contents

- [Overview](#overview)
- [Models](#models)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [License](#license)

## Overview

The goal of this project is to create accurate classifiers for different animal subspecies based on image data. We utilize deep learning techniques and pre-trained models like ResNet50, MobileNetV3, and DenseNet121 for efficient training.

## Models

The following models are available in this project:

- **ResNet50**: A deep residual network model for image classification.
- **MobileNetV3**: A lightweight model optimized for mobile and edge devices.
- **DenseNet121**: A densely connected convolutional network for efficient feature reuse.

### Accessing the Models

The models are hosted on Google Drive. You can download them from the following folder:

[**Animal Subspecies Classification Models**](https://drive.google.com/drive/folders/1amG7RqxqujTs5DDMLn1nexEp-KSVoR4U?usp=sharing)

Download the desired model file and follow the usage instructions to integrate it into your own classification pipeline.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/alys-source14/poai-image-classification.git
   cd animal_subspecies_classification
   ```

2. **Set Up Python Environment**
   It is recommended to use a virtual environment to manage dependencies. You can create one using the following commands:
   
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   Install the necessary Python libraries using:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Download the Model:**
   Download the model of your choice from the Google Drive folder linked above.

2. **Run the Classification Script:**
   Once the model is downloaded, use the following script to classify an image:

   ```bash
   python classify_image.py --model <path_to_downloaded_model> --image <path_to_image>
   ```
   Replace `<path_to_downloaded_model>` with the path to your downloaded model file and `<path_to_image>` with the path to the image you want to classify.

## 💡 Contributors
- **Alyssa Husna binti Jamarizan**
- **Izz Hakimi bin Khairul Adzha**
- **Alya Azwin binti Zamri**
- **Nur Sazahah binti Salauddin**

📌 **Course:** ISB46703 Principle of Artificial Intelligence  
📌 **Lecturer:** Sir Ahmad Zhafri Hariz bin Roslan

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
