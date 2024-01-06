This project is a web application built to recognize handwritten digits using deep learning. Below are key details and instructions for getting started:

# Visual Digit Recognizer
The Visual Digit Recognizer is a web-based tool that leverages a PyTorch-based deep learning model trained on the MNIST dataset to recognize and classify handwritten digits.

# Technology Used
- React Frontend: The frontend is developed using React, ensuring a responsive and modern user experience.
- Django Backend: Powered by Django, the backend manages requests, communicates with the deep learning model, and delivers results.
- database for storing the image in blob format.
- Pytorch for training the model: A CNN model was trained to recognize the digits with MNIST dataset.

  The Application uses a python library Speech Recognition which will call out the digit that the user has drawn 

# Architecture Diagram


# Sequence flow:
![image](https://github.com/ramprakashpg/visual-digit-recognizer/assets/68699055/18ba5bdb-1c33-4e7d-af3d-cf68d954d088)

# Key Features
1. Real-Time Recognition: Experience instant digit recognition by drawing digits on the canvas or uploading images.
2. User-Friendly Interface: The application provides a simple and intuitive interface for seamless interaction.
5. MNIST Trained Model: The heart of the project is a PyTorch model fine-tuned on the MNIST dataset for accurate digit classification.

# Getting Started
Clone the Repository:
```
git clone https://github.com/ramprakashpg/visual-digit-recognizer.git
cd visual-digit-recognizer
```

Install frontend dependencies:
```
npm install
```

Install backend dependencies:
```
pip install -r requirements.txt
```
Run the Application:

Start the Django backend (in a separate terminal)
Run the following command in the main directory
``` 
python manage.py runserver
```
Access the Application:
Open your web browser and navigate to http://localhost:3000 to interact with the Visual Digit Recognizer.

![image](https://github.com/ramprakashpg/visual-digit-recognizer/assets/68699055/c7b03d60-faa3-42b8-b8fb-4f0041120fc6)

