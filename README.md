🧠 Brain Tumor Detection using CNNs
Overview

The Brain Tumor Detection Project leverages Convolutional Neural Networks (CNNs) to automatically detect brain tumors in MRI images. This system aims to assist healthcare professionals by providing a reliable, accurate, and efficient diagnostic tool.

By utilizing Python, TensorFlow, and Keras, the project demonstrates the potential of deep learning in medical imaging to enhance healthcare outcomes and expedite the diagnostic process.
Features

    Automated Tumor Detection: Identifies brain tumors from MRI scans with a high degree of accuracy.
    Model Accuracy: Achieved 92% accuracy in classifying MRI images as tumor-positive or tumor-negative.
    Technology Stack:
        Frameworks: TensorFlow, Keras
        Programming Language: Python
        Libraries: NumPy, Pandas, Matplotlib, Seaborn

Motivation

The increasing prevalence of brain disorders necessitates faster and more accurate diagnostic tools. This project explores the use of deep learning models to support radiologists and improve diagnostic efficiency in healthcare.
Approach

    Data Preprocessing:
        MRI images were resized, normalized, and augmented to ensure robust training.

    Model Architecture:
        A Convolutional Neural Network (CNN) was designed and trained to identify patterns in MRI images.
        Layers:
            Convolution + Max Pooling
            Dropout for regularization
            Fully Connected Layer for classification

    Evaluation:
        Model performance was evaluated using metrics like accuracy, precision, and recall.

Results

    92% accuracy achieved on the validation dataset.
    Significantly reduces diagnostic time compared to manual assessments.

How to Run

    Clone the repository:

git clone https://github.com/SruthiRoyal12345/Brain-Tumor-Detection.git
cd Brain-Tumor-Detection

Install dependencies:

pip install -r requirements.txt

Train the model:

python train_model.py

Test the model:

    python test_model.py

Future Enhancements

    Include multi-class classification to differentiate between tumor types.
    Improve dataset diversity for better generalization.
    Deploy the model using a web interface or mobile app for real-world use.

Contact

For queries or collaboration, feel free to reach out:
📧 galisruthi013@gmail.com
🌐 GitHub Profile
