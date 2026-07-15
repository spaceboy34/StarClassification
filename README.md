# Stellar Object Classification

A machine learning project for classifying celestial objects using astronomical observation data. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction. As this project improves, it can be used to classify stellar objects as new discoveries are made.

---

## Video 

https://drive.google.com/file/d/1TdiO-XVum4zg5MfrmI-lGT7lUfSqmV5i/view?usp=drive_link
This video demonstrates the model on an image of a star and an image of a galaxy.

## Project Overview

The goal of this project is to accurately classify astronomical objects based on observational features collected from sky surveys. The classification model is trained using supervised machine learning techniques to distinguish between different types of stellar objects.

This repository was created as part of a data science and machine learning portfolio project, showcasing best practices in data preprocessing, feature engineering, model evaluation, and reproducible experimentation.

---

## Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Multiple machine learning models
* Model evaluation and comparison
* Prediction on unseen data
* Well-documented and reproducible workflow

---


## Technologies Used

Python
PyTorch
NVIDIA Jetson Inference
TorchVision
ResNet-18
ONNX

---

## Machine Learning Workflow

1. Load dataset
2. Clean and preprocess data
3. Perform exploratory data analysis
4. Engineer relevant features
5. Split data into training and testing sets
6. Train machine learning models
7. Evaluate performance using classification metrics
8. Save the best-performing model

---

## Evaluation Metrics

Model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

## Installation

Clone the repository:

```bash
git clone https://github.com/spaceboy34/StarClassification.git
cd StarClassification
```

## Usage

Enter the correct folder:
'''bash
cd jetson-inference
'''

'''bash
./docker/run.sh
'''

'''bash
cd python/training/classification
'''

Run the training script:

```bash
python3 train.py --model-dir=models/stellar_class4 data/stellar_expanse
```

## Example Results

The trained model classifies stellar objects (including galaxies, nebulas and stars) using astronomical features extracted from the dataset.

Example outputs include:

* Confusion Matrix
* Feature Importance
* Model Accuracy
* Performance Comparison Charts

---

## Future Improvements

* Hyperparameter optimization
* Deep learning models
* Cross-validation
* Model deployment with Flask or FastAPI
* Interactive web dashboard
* Automated data pipeline
* Improve star and nebula accuracy
* Add more classes
* Retrain model with more data

## Notable Problems
* The model occasionally misidentifies stellar objects most likely due to the fact that not enough images were collected

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

**Ethan**

GitHub: https://github.com/spaceboy34

---

## Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
