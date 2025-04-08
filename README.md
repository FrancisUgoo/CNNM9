# Facial Expression Recognition Deep Learning Model

Welcome to the **Facial Expression Recognition** project! This open-source project aims to build deep learning models capable of recognizing and classifying 9 distinct facial expressions in real-time. The expressions include:

- **Happy**
- **Sad**
- **Fear**
- **Anger**
- **Disgust**
- **Surprise**
- **Pain**
- **Tired/Exhausted**
- **Neutral**

The project utilizes **Python**, **Keras**, and **TensorFlow** to train and deploy the models.

## Project Overview

This project involves training deep learning models to classify facial expressions based on images. It has been developed with experimentation in mind and serves as a foundation for future improvements and research. The models were trained on a dataset of facial images, and several different approaches have been explored during the research phase.

While the project is experimental and not yet fully finished, it is open-source and welcomes contributions from anyone interested in improving or extending the model. You are encouraged to use, modify, and enhance the project to suit your needs.

## Project Structure

This repository contains the following key components:

### 1. **test.zip**
Contains the zipped test dataset of images used for evaluating the models.

### 2. **training.zip**
Contains the zipped training dataset of images used to train the models.

### 3. **models folder**
This folder contains the models that were created during the research and experimentation phase. The models are based on various architectures and approaches to better understand their performance in facial expression classification.

### 4. **preferred_model.7z**
The final, preferred model after the research process. This model has been optimized for facial expression recognition.

### 5. **haarcascades folder**
Contains several pre-trained Haar Cascade XML files for face detection, which are essential for detecting faces in images before classifying the expressions.

### 6. **haarcascade_frontalface_default.xml**
This specific Haar Cascade file was chosen and used in the final model for detecting frontal faces in the input images.

### 7. **proj.ipynb**
The primary Python notebook where the project was developed. This notebook contains the entire process of training, evaluating, and saving the models. It showcases the step-by-step approach used to build the model.

### 8. **matplot.ipynb**
A Jupyter notebook used to present the results of the model in visual form. It leverages **Matplotlib** to graph and analyze the accuracy and performance of the different models.

### 9. **snap.ipynb**
A Jupyter notebook used to test the face capture and real-time prediction process. It interacts with the webcam to capture facial expressions and classify them in real-time.

### 10. **epochs_to_show_accuracy folder**
Contains `.txt` files that document the prediction results at different phases of the research. These files showcase the accuracy and performance metrics of the models created during experimentation.

## Purpose of the Project

The main goal of this project is to develop a real-time facial expression recognition system that can classify nine distinct facial expressions. The project was built using deep learning techniques with Python, TensorFlow, and Keras. After full testing and adaptation, the system can be integrated into various applications, including emotion-based AI, interactive systems, or mental health monitoring tools.

## Getting Started

### Prerequisites

To run this project locally, you'll need to install the following dependencies:

- Python 3.x
- Keras
- TensorFlow
- OpenCV
- Matplotlib

You can install the necessary libraries by running:

```bash
pip install -r requirements.txt
```

### Usage

1. **Data Preparation:**
   - Unzip the `training.zip` and `test.zip` files into their respective directories to prepare the training and test datasets.

2. **Training the Model:**
   - Open the `proj.ipynb` notebook to begin training the model. It includes the full pipeline from preprocessing the data to training and saving the model.

3. **Testing and Real-Time Prediction:**
   - Use the `snap.ipynb` notebook to test the real-time capture and prediction process. This notebook interacts with your webcam and predicts the facial expression of the user.

4. **Model Evaluation:**
   - Use `matplot.ipynb` to visualize the results and accuracy of the models. It will help you understand how well the model is performing and analyze areas for improvement.

5. **Using the Preferred Model:**
   - The `preferred_model.7z` contains the final optimized model. You can test this model directly in real-time applications or for further evaluation.

## Contributing

This project is in its experimental phase, and improvements are always welcome! If you have ideas for enhancing the model or improving the code, please feel free to fork the repository, make changes, and submit a pull request.

Some ideas for improvement:
- Experiment with different neural network architectures (e.g., ResNet, VGG).
- Implement data augmentation techniques to increase model robustness.
- Fine-tune the models on different datasets for better generalization.
- Improve real-time prediction speed and accuracy.

## License

This project is open-source and licensed under the MIT License. You are free to use, modify, and distribute the code.

## Acknowledgments

This project uses several open-source tools and libraries, including:
- **TensorFlow** and **Keras** for deep learning.
- **OpenCV** for face detection.
- **Matplotlib** for result visualization.

---

Feel free to explore, experiment, and contribute to this project. Together, we can create even better models for facial expression recognition!
