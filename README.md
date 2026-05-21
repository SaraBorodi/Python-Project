# Salary Classification using k-NN

This project uses the k-Nearest Neighbors (k-NN) algorithm to classify employee salaries into three categories: low, medium, and high.

The classification is based on features such as:
- years of experience
- education level
- industry
- certifications
- company size
- remote work
- skills count

The dataset contains 250,000 employee records downloaded from Kaggle.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Google Colab

## Project Steps

- Data loading and preprocessing
- Missing value verification
- Salary classification using quantiles
- One-hot encoding for categorical data
- Data scaling using StandardScaler
- Train/test split
- k-NN model training
- Accuracy evaluation and confusion matrix visualization

## Results

The model was tested using multiple values of `k`.

Best result:
- k = 18
- Accuracy ≈ 72%

The model performed well for low and medium salary classes, while the high salary category was more difficult to classify.

## What I Learned

Through this project I gained practical experience with:
- Machine Learning workflows
- Data preprocessing
- Classification algorithms
- Feature encoding
- Model evaluation
- Data visualization

## Author

Sara Borodi

GitHub:
https://github.com/SaraBorodi
