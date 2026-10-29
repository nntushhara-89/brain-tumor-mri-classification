# 🧠 Brain Tumor MRI Classification Using CNN

A deep learning project that classifies brain MRI images into four categories using a **Convolutional Neural Network (CNN) built from scratch** with TensorFlow and Keras.

## 📌 Project Overview

Brain MRI images can contain different patterns that are useful for studying brain tumors. This project explores image classification by training a CNN to recognize four categories of MRI images.

The model is trained from scratch rather than using a pretrained neural network.

**Note:** This project is for educational purposes only. It is not a medical diagnostic tool.

## 🎯 Objectives

- Classify brain MRI images into four categories.
- Build a CNN using TensorFlow and Keras.
- Preprocess and normalize MRI images.
- Train and evaluate the model.
- Analyze results using accuracy, precision, recall, F1-score, and a confusion matrix.

## 🗂️ Dataset

The project uses the Brain Tumor MRI Dataset from Kaggle.

**Dataset link:** [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

The dataset contains four classes:

| Class | Description |
|---|---|
| Glioma | MRI images categorized as glioma |
| Meningioma | MRI images categorized as meningioma |
| No Tumor | MRI images categorized as no tumor |
| Pituitary | MRI images categorized as pituitary |

The dataset is organized into training and testing folders. The dataset itself is not included in this repository.

## 🛠️ Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow

## 🧠 CNN Architecture

The CNN is created from scratch and includes:

1. Input layer for 128 × 128 RGB images
2. Convolution layer with 32 filters
3. Convolution layer with 64 filters
4. Convolution layer with 128 filters
5. Convolution layer with 256 filters
6. Max-pooling layers
7. Flatten layer
8. Dense layer with 128 units
9. Dropout layer
10. Softmax output layer with four classes

The model uses the Adam optimizer and sparse categorical cross-entropy loss.

## ⚙️ Project Workflow

1. Download and extract the dataset.
2. Inspect the dataset folders and image classes.
3. Visualize sample MRI images.
4. Resize images to 128 × 128 pixels.
5. Normalize pixel values to the range 0–1.
6. Build the CNN from scratch.
7. Train the model for 10 epochs.
8. Plot training and validation accuracy and loss.
9. Evaluate predictions using a classification report and confusion matrix.
10. Save the trained model in Keras format.

## 📊 Evaluation

The project evaluates the model using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Training and validation curves

The actual numerical results should be taken from the completed Google Colab notebook. The testing dataset was also used for validation during training, so the reported results should not be considered a fully independent final evaluation.

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Download the dataset from the Kaggle link above.
3. Configure Kaggle access in Colab if downloading through the Kaggle API.
4. Run the notebook cells in order.
5. Train the CNN and review the evaluation results.

## 💾 Model File

The trained model is saved as `brain_tumor_cnn.keras`.

The model file is not included in this repository because of its size. Run the notebook to recreate it.

## 🔮 Future Improvements

- Add data augmentation.
- Tune hyperparameters and train for additional epochs.
- Use a separate validation set and reserve the test set for final evaluation.
- Compare different CNN architectures.
- Add a simple interface for uploading an MRI image and viewing the predicted class.

## 👩‍💻 Author

**Tushhara N.**

GitHub: [nntushhara-89](https://github.com/nntushhara-89)

---

If you find this project useful, feel free to ⭐ the repository.

