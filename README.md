# Vehicle Image Classification

## Overview

This project focuses on **vehicle image classification using Deep Learning**.

The model learns visual features from vehicle images and classifies them into different vehicle categories.

The project uses the **Vehicles** dataset, which contains images belonging to seven different vehicle classes.

## Dataset

The dataset used in this project is **Vehicles**.

It contains the following **7 classes**:

1. Auto Rickshaws
2. Bikes
3. Cars
4. Motorcycles
5. Planes
6. Ships
7. Trains

The images are organized into separate folders according to their vehicle class.

## Dataset Structure

```text
Vehicles/
│
├── Auto Rickshaws/
├── Bikes/
├── Cars/
├── Motorcycles/
├── Planes/
├── Ships/
└── Trains/
```

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Deep Learning
* Image Classification

## Project Workflow

1. Load the **Vehicles** dataset.
2. Organize images according to their classes.
3. Preprocess and resize the images.
4. Normalize the image data.
5. Split the dataset into training and validation/testing sets.
6. Build the Deep Learning classification model.
7. Train the model on vehicle images.
8. Evaluate the model performance.
9. Test the model using new vehicle images.
10. Predict the vehicle category.

## Classification Classes

```text
Auto Rickshaws
Bikes
Cars
Motorcycles
Planes
Ships
Trains
```

## Model Workflow

```text
Vehicle Images
      ↓
Image Preprocessing
      ↓
Training Dataset
      ↓
Deep Learning Model
      ↓
Model Training
      ↓
Image Classification
      ↓
Predicted Vehicle Class
```

## Example

```text
Input Image
     ↓
    Model
     ↓
Prediction: Cars
```

The model predicts one of the seven vehicle categories based on the input image.

## Key Learning

This project provided practical experience with:

* Image Classification
* Deep Learning
* Image Preprocessing
* Dataset Organization
* Model Training
* Model Evaluation
* Image Prediction
* TensorFlow and Keras

## Project Structure

```text
Vehicle_Image_Classification/
│
├── Vehicle-Image-Classification.ipynb
├── Vehicles/
│   ├── Auto Rickshaws/
│   ├── Bikes/
│   ├── Cars/
│   ├── Motorcycles/
│   ├── Planes/
│   ├── Ships/
│   └── Trains/
│
├── README.md
└── requirements.txt
```

> The exact project files may vary depending on the project version.

## Future Improvements

* Improve classification accuracy.
* Apply data augmentation.
* Experiment with different CNN architectures.
* Use transfer learning with pretrained models.
* Add more vehicle categories.
* Deploy the trained model as a web application.

## Author

**M Arshad**

GitHub: **M-Arshad784**
