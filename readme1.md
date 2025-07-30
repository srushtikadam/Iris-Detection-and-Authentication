👁️ Project Overview
Iris recognition is one of the most reliable forms of biometric authentication. This project leverages CNNs to detect, preprocess, segment, and authenticate iris images in real-time, supported by a GUI.
🚀 Features
•	• Iris image acquisition and preprocessing
•	• Image segmentation using chan_vese algorithm
•	• Deep learning model training with CNN for classification
•	• Real-time iris prediction and user authentication
•	• Graphical User Interface (GUI) for end-to-end testing
🧠 Technologies Used
•	• Python 3.7+
•	• OpenCV
•	• TensorFlow / Keras
•	• Tkinter GUI
•	• Matplotlib
•	• Scikit-image
•	• Augmentor
📁 Directory Structure
data/ - Original dataset
Preprocessed/ - Augmented & preprocessed dataset
model/ - Trained model (iris.h5)
gui/ - GUI files for preprocessing, segmentation, and prediction
utils/ - Image utilities like filters, segmentation
main.py - Main GUI runner
README.md - Project documentation
🏗️ How It Works
•	• Image Acquisition: Users can load and preprocess iris images through the GUI.
•	• Segmentation: Images are segmented to isolate the iris region.
•	• Model Training: CNN is trained on processed iris images to classify and recognize individual users.
•	• Prediction: The model predicts and verifies iris patterns and maps them to authorized users.
•	• Authentication: A login interface allows only recognized users to proceed.
📊 Results
• Achieved 99-100% accuracy on test data.
• Robust against variations in lighting and iris size.
• Supports real-time authentication via GUI.
🖥️ Requirements
Python 3.7+
•	• opencv-python
•	• tensorflow
•	• matplotlib
•	• Pillow
•	• Augmentor
•	• scikit-image
•	• tkinter
Install via:

pip install -r requirements.txt
📷 GUI Preview
• Image preprocessing and segmentation
• Iris prediction window
• Secure login page post-prediction
🛡️ Applications
•	• Secure access control (offices, labs)
•	• Financial services authentication
•	• Border control and e-passport systems
•	• Healthcare records security
•	• Smartphone biometric security

