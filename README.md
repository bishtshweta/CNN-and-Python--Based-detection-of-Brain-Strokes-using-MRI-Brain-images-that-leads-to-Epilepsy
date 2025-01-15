# CNN-and-Python--Based-detection-of-Brain-Strokes-using-MRI-Brain-images-that-leads-to-Epilepsy
The project uses CNNs to detect brain strokes from MRI scans, achieving 90.55% test accuracy. Key steps include data preprocessing, augmentation, and using the VGG16 model. It aims to reduce diagnosis time, cost, and errors. The model shows potential for medical use, with scope for improvement through larger datasets and optimized hyperparameters.
Title:
Detection of Brain Stroke Using MRI Brain Images That Leads to Epilepsy

Objective:
Develop a CNN-based model to classify stroke-affected and normal brain MRI images with high accuracy and minimal human error.
Key goals: High accuracy, reduced medical tests, cost efficiency, faster diagnosis, and reduced mortality rates.
Introduction:
A stroke is a sudden loss of brain function due to disturbed blood flow, potentially causing epilepsy due to brain damage.
Current detection methods rely heavily on human expertise, which can be error-prone and time-consuming.
Dataset:
MRI images sourced from med.harvard.edu.
Dataset includes 250 images (100 normal, 150 stroke-affected).
Proposed Methodology:
MRI Image Acquisition: Collecting relevant MRI brain images.
Pre-processing: Normalization and preparation of images.
Data Augmentation: Using techniques like rotation, flipping, and brightness adjustments to enhance dataset variety.
Feature Extraction: Leveraging DenseNet-169 and CNN models.
Classification: Using Random Forest, SVM, and optimized CNNs for accurate predictions.
Network Architecture:
Experiments included MLP, SVM with HoG, and CNNs.
Transfer learning models (ResNet, VGG16, VGG19) were tested, with VGG16 providing the best results.
Results:
Training Accuracy: 91.09%
Test Accuracy: 90.55%
Validation showed robust performance with effective optimization.
Conclusion:
A robust CNN model was created with high accuracy using limited data.
Data augmentation and transfer learning significantly improved results.
Future enhancements include using larger datasets and advanced hyperparameter tuning.
References:
Studies and publications on stroke detection and deep learning methodologies were cited to support the project.
