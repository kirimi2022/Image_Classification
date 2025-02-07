🍠 Potato Leaf Disease Classification
Author: Dennis Mwenda
Project Type: Deep Learning-based Image Classification
Deployment Platform: Gradio Application

📋 Project Description
This project focuses on building a deep learning model to classify potato leaf images into one of the following categories:

Early Blight
Healthy
Late Blight
The model was trained using a Convolutional Neural Network (CNN) to detect diseases in potato leaves. This helps farmers and agricultural experts identify and manage diseases early, improving yield and quality.

🚀 Objective
The primary objective of this project is to create a user-friendly web application for classifying potato leaf diseases using image inputs. The application is built using Gradio, allowing users to upload images of potato leaves and get instant predictions.

🛠️ Libraries and Tools Used
TensorFlow/Keras: Model training and loading
Gradio: Creating an interactive web interface for deployment
NumPy: Numerical computations
PIL (Pillow): Image preprocessing
📊 Model Details
The saved model (3.h5) is a Convolutional Neural Network (CNN) trained on a dataset of potato leaf images. It expects input images resized to 128x128 pixels and normalized. The output is a prediction of the most likely class with confidence percentage.

Class Labels:

Early Blight
Healthy
Late Blight
📸 Application Workflow
Upload an image of a potato leaf.
The image is preprocessed (resized and normalized).
The trained CNN model classifies the image into one of the three classes.
The result, along with confidence percentage, is displayed.
🖥️ How to Run the Gradio App
Install the required libraries:

bash
Copy
Edit
pip install tensorflow gradio numpy pillow
Run the Python script:

bash
Copy
Edit
python app.py
Open the Gradio interface in your browser (it will automatically launch at http://localhost:7860).

📈 Expected Results
Early Blight: Leaves show brown spots with yellow halos.
Healthy: Leaves are fresh green without spots or discoloration.
Late Blight: Dark spots with water-soaked appearance and rapid yellowing.
🧪 Example Prediction
Image	Prediction	Confidence
Healthy	95.80%
Early Blight	88.65%
Late Blight	92.30%
🌟 Future Improvements
Incorporate more disease categories.
Deploy the application on the web (e.g., Hugging Face Spaces or Heroku).
Add real-time image capture support from mobile devices.
📬 Contact
For any questions or feedback, feel free to reach out at dennismwenda@example.com
