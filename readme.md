# Plant Disease Detection using CNN

This project uses a Convolutional Neural Network (CNN) to detect **crop diseases** from images. The model is trained using TensorFlow and Keras on a dataset of plant leaves categorized by diseases. It is capable of classifying various plant diseases accurately and is suitable for deployment in smart agriculture systems.

---

## Dataset

The dataset is taken from here **https://www.kaggle.com/datasets/jawadali1045/20k-multi-class-crop-disease-images?select=Train** 

---

## Features

-  Image classification with CNN
-  Training/Validation accuracy & loss visualization
-  Confusion matrix for performance evaluation
-  Classification report
-  Predictions with image visualization
-  Model saving and loading

---

## Training the Model
Run the training notebook with:

- Epochs: 5
- Image size: 128x128
- Batch size: 32
- EarlyStopping to prevent overfitting

--- 

## Plots and evaluations include:

- Accuracy & loss curves
- Confusion matrix
- Classification report
- Sample predictions

--- 

## Sample Prediction

- Displays random samples from the validation set with predicted and actual labels.
![alt text](<crop disease samples.png>)
![alt text](<crop disease sample1.png>)
![alt text](<crop disease sample2.png>)

---

## Future Improvements

- Increase dataset size or use more augmentations
- Train with more epochs for better performance
- Add model explainability tools (like Grad-CAM)
- Deploy as a web app for real-time predictions
