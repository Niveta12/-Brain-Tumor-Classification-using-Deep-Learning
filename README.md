# -Brain-Tumor-Classification-using-Deep-Learning
This project focuses on Brain Tumor Classification using Deep Learning. It leverages a Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify MRI brain scans.


📌**Introduction:**


This project implements a Convolutional Neural Network (CNN) to classify brain MRI scans into four categories:

1. Glioma Tumor

2. Meningioma Tumor

3. Pituitary Tumor

4. No Tumor

Brain tumor detection is a critical task in medical imaging. Automating this process with deep learning helps in early diagnosis, treatment planning, and reducing human error.

  **Key steps include:**

  • Data preprocessing and augmentation using ImageDataGenerator

  • Training a CNN model with multiple convolutional, pooling, and dropout layers to avoid overfitting

  • Evaluation of the model using accuracy, loss, and confusion matrix visualization with seaborn

  • Achieving robust classification performance to support early detection of brain tumors

  • This project highlights the power of deep learning in medical imaging and how CNNs can aid in computer-aided diagnosis.


🔑**Tech Stack:**

Languages: Python

Libraries: TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

Dataset: MRI Brain Tumor images (Training + Testing split)


🏗️**Model Architecture**

The CNN model was built using TensorFlow/Keras with the following layers:

‣ Convolutional + MaxPooling layers for feature extraction

‣ Dropout layers to reduce overfitting

‣ Fully connected Dense layers

‣ Softmax activation for multi-class classification


📊**Results**

✔ Achieved strong classification performance on test images

✔ Visualized accuracy/loss curves and confusion matrix

✔ Model successfully distinguishes between different tumor types and normal scans


🚀**Future Work**

⇢ Improve accuracy with transfer learning (e.g., VGG16, ResNet, EfficientNet)

⇢ Deploy as a web app for real-world usability

⇢ Train on larger, more diverse medical imaging datasets


