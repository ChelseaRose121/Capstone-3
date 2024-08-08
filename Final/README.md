Brain Tumor Classification using CNN
Project Overview
This project aims to develop a convolutional neural network (CNN) model to detect and classify different types of brain tumors from MRI images. The model is designed to assist medical professionals in the early and accurate diagnosis of brain tumors, ultimately contributing to better patient outcomes through timely and targeted treatment interventions.

Dataset
The dataset used for this project consists of MRI images of brain scans categorized into four classes:

Glioma
Meningioma
No Tumor
Pituitary Tumor

Training Data
Glioma: 1321 images
Meningioma: 1339 images
No Tumor: 1595 images
Pituitary Tumor: 1457 images

Testing Data
Glioma: 300 images
Meningioma: 306 images
No Tumor: 405 images
Pituitary Tumor: 300 images

Preprocessing
Removed blurred images to enhance clarity and reliability.
Normalized pixel values to a range of 0 to 1.
Encoded labels into numerical values.
Split data into training (80%) and testing (20%) sets.
Applied data augmentation techniques for a diverse dataset.

Model Architecture
Convolutional Neural Network (CNN) with the following layers:
Conv2D layers with ReLU activation
MaxPooling2D layers
Dropout layers to prevent overfitting
Flatten layer
Dense layers with ReLU and softmax activation

Training
Trained the model for 20 epochs.
Used early stopping to prevent overfitting.
Achieved a test accuracy of 94.95%.
Evaluation

Confusion matrix and classification report to assess model performance.
High precision and recall rates for all classes.
Overall accuracy of 0.95, with both macro and weighted averages of precision, recall, and F1-score at 0.95.

Recommendations
Integrate the model into clinical practice to enhance early detection and treatment of brain tumors.
Regularly update and refine the model using larger and more diverse datasets.
Develop user-friendly interfaces for seamless integration into existing medical imaging systems.

Future Work
Enhance data quality and quantity.
Explore advanced architectures such as 3D CNNs and ensemble methods.
Validate the model in real-world clinical settings.
Integrate additional clinical data for a comprehensive diagnostic tool.

Usage
To run the model and evaluate its performance, use the provided Jupyter Notebook. Ensure all necessary libraries are installed and the dataset is properly loaded.

For more detailed instructions and code, refer to the project notebook and associated files.


