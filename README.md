# Traffic-Forecasting-for-Intelligent-Transport-Systems
.

🚦Traffic Forecasting for Intelligent Transport Systems
This project uses a Convolutional Neural Network (CNN) to detect road conditions such as:

🟢 Low Traffic

🔴 Heavy Traffic

🚗 Accident

🔥 Fire Accident

We used the TRAFFICNET dataset and built a Tkinter-based GUI to interact with the model.

📁 Features
GUI built using Tkinter

CNN model trained with traffic images

Predicts traffic type from uploaded images

Accuracy & Loss graph visualization

🧠 Technologies Used
Python

Tkinter (for GUI)

Keras / TensorFlow (for CNN)

TRAFFICNET Dataset (from GitHub)

🚀 How to Run the Project
Step 1: Install Required Libraries
bash
Copy
Edit
pip install tensorflow keras pillow numpy
Step 2: Run the Application
Double-click on run.bat
OR
Open terminal and run:

bash
Copy
Edit
python main.py
🧪 How It Works (Step-by-Step)
Upload Dataset
Click on "Upload Dataset" and select the trafficnet_dataset folder.

Image Preprocessing
Click on "Image Preprocessing" to resize and convert images into a CNN-friendly format.

Generate CNN Model
Click "Generate CNN Traffic Model". The model will train and show training accuracy (~99%).

Predict Traffic Condition
Click "Upload Test Image & Predict Traffic", choose an image, and the model will classify it.

View Accuracy & Loss Graph
Click on "Accuracy & Loss Graph" to see how well the model trained over time.

📊 Output Sample
Model Accuracy: 99%

Classes: Low Traffic, Heavy Traffic, Accident, Fire Accident

📦 Dataset Source
TRAFFICNET dataset available freely on GitHub
(Provide actual link if available)

📌 Note
This is an academic prototype — backend and model are local, not deployed online.

All processing happens locally, no external APIs used.

