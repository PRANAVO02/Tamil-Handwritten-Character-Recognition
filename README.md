# Handwritten Tamil Character Recognition Using CNN

This project implements an end-to-end deep learning system for recognizing handwritten Tamil characters using Convolutional Neural Networks (CNNs). Designed to tackle the challenges of the complex Tamil script and diverse handwriting styles, this solution aids in digitization, education, and preservation of the Tamil language.

🚀 Features
🧠 Custom CNN architecture tailored for Tamil character recognition

🔤 Supports 156 unique Tamil characters

🖼️ Preprocessing pipeline including grayscale, resizing, and normalization

📊 Model evaluation with accuracy, precision, recall, F1-score, and confusion matrix

🛠️ Real-time handwritten character prediction from scanned or uploaded images

📁 Dataset
Source: Public dataset containing handwritten Tamil characters

Classes: 156 Tamil characters

Structure: Organized into subfolders by character label

Split: 80% training and 20% testing

🔧 Preprocessing Steps
Each input image undergoes the following steps before training:

✅ Grayscale Conversion – reduces complexity

✅ Resizing – standardized to 32×32 pixels

✅ Normalization – pixel values scaled to [0, 1]

✅ Label Encoding – converts character labels to numerical format

🧠 Model Architecture
A custom Convolutional Neural Network is built with:

Multiple Convolutional Layers for feature extraction

Max Pooling Layers to reduce dimensionality

Dropout Layers for regularization

Dense Layers followed by a softmax output for classification

Loss Function: Categorical Crossentropy
Optimizer: Adam
Metrics: Accuracy

📈 Evaluation
Accuracy – measures overall correctness

Precision, Recall, F1-Score – assess class-wise performance

Confusion Matrix – visualize correct vs. incorrect predictions

🖥️ Prediction & Deployment
After training:

Input handwritten image is preprocessed

The trained model predicts the character class

Output is displayed or used in downstream systems (OCR, language tools, etc.)


🧪 Usage

Train the Model

python train_model.py

Evaluate Performance

python evaluate_model.py

Predict a New Image

python predict_image.py 

📚 Applications
📝 Optical Character Recognition (OCR) for Tamil script

📖 Digitization of handwritten documents and manuscripts

🎓 Educational tools and Tamil language apps

🗂️ Archival and cultural documentation efforts
