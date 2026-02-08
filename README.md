# Brain Tumor Detection & Classification Using CNN
Title: Problem Statement & Motivation
Content:
•	Brain tumors are difficult to diagnose manually from MRI images
•	Manual diagnosis is time-consuming and prone to human error
•	Early and accurate detection is crucial for patient treatment
•	Deep Learning can automate tumor detection and classification
•	Objective: Build an AI system to classify brain tumors from MRI scans
____________________________________________
Title: Tools & Technologies
Content:
•	Python
•	CNN (Convolutional Neural Network)
•	OpenCV – Image preprocessing & segmentation
•	Keras / TensorFlow – Model training
•	Tkinter – Desktop GUI
•	SQLite – Database for login & records
•	Matplotlib – Accuracy & loss visualization
___________________________________________
🔄 System Architecture / Workflow

Content (Flow Diagram Style):
User Login/Registration
⬇
MRI Image Upload
⬇
Preprocessing (Resize, Grayscale)
⬇
Segmentation (Thresholding using OpenCV)
⬇
CNN Feature Extraction
⬇
Tumor Classification
⬇
Prediction Output + Execution Time
__________________________________________
🧪  Dataset & Preprocessing
Content:
•	MRI images used for training and testing
•	Image resizing to 100×100
•	Normalization (pixel scaling)
•	Data augmentation (zoom, shear, flip)
•	Grayscale conversion
•	Threshold-based segmentation using OpenCV
___________________________________________
🧠CNN Model Architecture
Title: CNN Architecture
Content:
•	Multiple Convolution Layers
•	Max Pooling Layers
•	Flatten Layer
•	Fully Connected Dense Layers
•	Dropout for overfitting control
•	Output Layer (4 Classes):
o	Normal
o	Glioma
o	Meningioma
o	Pituitary
________________________________________
💻  GUI & Database
Content:
•	Tkinter-based desktop application
•	Features:
o	Registration
o	Login
o	Image Upload
o	Preprocessing
o	Prediction
•	SQLite database stores:
o	User credentials
o	Login details
•	Displays prediction results & execution time
________________________________________
📊 Results & Performance
Content:
•	Model achieved high accuracy
•	Displays:
o	Tumor Type
o	Execution Time
•	Training vs Validation Accuracy Graph
•	Training vs Validation Loss Graph
•	Real-time prediction using saved model
________________________________________
🚧  Challenges & Future Scope
Content:
Challenges:
•	MRI image quality variations
•	Overfitting
•	Segmentation accuracy

Future Scope:
•	Use Transfer Learning (VGG16, ResNet)
•	Deploy as Web App (Streamlit / Flask)
•	Add password hashing for security
•	Use U-Net for better segmentation
•	Support 3D MRI scans
________________________________________
✅ Conclusion
Content:
•	Successfully built an end-to-end brain tumor detection system
•	Combined Deep Learning with Image Processing
•	Achieved automated classification of tumor types
•	System provides fast prediction with execution time
•	Can assist doctors in early diagnosis and decision-making




