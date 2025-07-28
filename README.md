#  Cats vs Dogs Image Classifier (Deep Learning Project)

This is my first deep learning project, where I built a binary image classifier to distinguish between cats and dogs using a Convolutional Neural Network (CNN). The project includes model training, evaluation, and deployment through a Flask web app.

##  Overview

- **Model**: Custom CNN built with TensorFlow & Keras
- **Dataset**: 
  - 8,005 training images
  - 2,023 validation images
  - 2 classes (cats and dogs)
- **Accuracy**: 
  - Validation Accuracy ~74%
- **Deployment**: Flask-based web app where users can upload an image and receive a live prediction

##  Model Architecture

- Convolutional layers with ReLU activation
- MaxPooling layers to reduce spatial dimensions
- Dense output layer with softmax activation
- Data augmentation and dropout for generalization

> **Note**: Input images are resized to `256x256` during preprocessing.

##  Web App Features

- Upload an image of a cat or dog
- Get prediction (Cat or Dog) with a confidence score
- Clean and simple UI

##  Project Structure
cats-vs-dogs-classifier/
│
├── templates/ # HTML frontend
├── model/ # Saved model (.keras or .h5)
├── app.py # Flask server
├── README.md
└── requirements.txt

##  How to Run Locally

 Clone the repo:

Install dependencies:
pip install -r requirements.txt

Start the Flask server:
python app.py

Open http://127.0.0.1:5000/ in your browser.

 Model Download
Due to GitHub's file size limit (100MB), the trained model is hosted externally:

Download model.keras from https://huggingface.co/Fatimazunaira/Cats_vs_Dogs_Model
After downloading, place it in the model/ folder.

Create a folder named 'uploads' for images
 Author
Fatima Zunaira
