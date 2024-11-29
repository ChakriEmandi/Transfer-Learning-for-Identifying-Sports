# Sports Classification Using EfficientNetB0
This project implements Transfer Learning with EfficientNet to classify 100 different types of sports. It consists of two main components: a training script in a Jupyter notebook and a Flask-based web application for real-time image classification.

## Features
### Model Architecture: EfficientNetB0, a state-of-the-art deep learning model for image classification.
### Extensive Dataset: Trained on 100 diverse sports categories, ranging from traditional games to modern sports.
### Flask Web Application: Allows users to upload an image and get predictions with a probability score.
### Pre-trained Model: The project leverages Transfer Learning, significantly reducing training time while achieving 97% accuracy.

## File Structure
sports-classification-efficientnet.ipynb: Contains the complete training process, including data preprocessing, model building, training, and evaluation.
app.py: Flask application to serve predictions.
sports_model_efficient_net.h5: Pre-trained model saved for deployment.
templates/index.html: Frontend interface for the web app.
requirements.txt: List of required Python libraries.

## Setup Instructions
Clone the Repository
git clone <repository-url>
cd sports-classification-efficientnet
Install Dependencies
Install necessary Python libraries
Run the Flask Application
Start the server to use the web application:

## python app.py
The application will be accessible at http://127.0.0.1:5000/.
## Usage
Open the web application in a browser.
Upload an image of a sport using the provided form.
The app will display the predicted sport along with a confidence score.
## Model Details
Preprocessing: Images are resized to 224x224 and normalized using EfficientNet's preprocessing pipeline.
Prediction: Outputs the most likely sports class with the associated probability.
## Future Work
Enhance model accuracy with additional data and fine-tuning.
Deploy the application on a cloud platform for wider accessibility.
Add support for video classification.
## Acknowledgements
Model: EfficientNetB0

Dataset: https://www.kaggle.com/datasets/gpiosenka/sports-classification

Framework: TensorFlow/Keras

Flask: Lightweight web application framework.
