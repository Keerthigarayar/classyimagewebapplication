# classyimagewebapplication
ImageClassifierWeb is a web application that allows users to upload images and get real-time classification results using a pre-trained TensorFlow model. This project leverages Flask for the backend server and TensorFlow's MobileNetV2 model for image classification. 

 Technology Stack
Backend: Flask (Python)
Machine Learning: TensorFlow with MobileNetV2 model
Frontend: HTML, CSS
Image Handling: Pillow (Python Imaging Library)
Installation
To get started with this project, follow these steps:

Clone the Repository:
git clone https://github.com/keerthigarayar/ImageClassifierWeb.git

cd ImageClassifierWeb
Create a Virtual Environment:
python -m venv venv

source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies:
pip install flask tensorflow pillow
Run the Application:
python app.py
Open your web browser and navigate to http://127.0.0.1:5000/ to access the application.

Usage
Go to the homepage of the application.
Use the upload form to select and upload an image.
The application will classify the image and display the top 3 predictions with their confidence scores.
git clone https://github.com/keerthigarayar/ImageClassifierWeb.git




