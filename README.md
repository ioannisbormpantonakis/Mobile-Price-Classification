# Mobile Price Classification

## Description
Small project experimenting with dimensionality reduction techniques (PCA, LDA) and a small PyTorch Multi Layer Perceptron (MLP).  
The dataset includes 2000 samples (mobile phones) with 20 features. Each sample is labeled with a class (0, 1, 2, 3) based on its price.  
  
## Details  
The project is split into 4 parts:

1. Preprocessing  
Boxplots for numeric and countplots for binary/categorical features.

2. PCA search  
Grid search over PCA hyperparameters with vanilla Naive Bayes classifiers.
Plot results of selected models.

3. LDA search  
Grid search LDA with vanilla Naive Bayes classifiers.
Plot results of selected models.

4. NN search  
Train a selected MLP, plot train/cv loss curves and report results


## How To Run
1. Install python 3.10 and the required packages in **requirements.txt**.

2. Download the Mobile Price Classification dataset **train.csv** from Kaggle website:

3. Create a folder named **data** and put **train.csv** inside it.

4. Open the four **.ipynb** notebooks and run the code for each part.

## References

Dataset  
https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

Libraries  
Numpy: https://numpy.org/  
Pandas: https://pandas.pydata.org/  
Matplotlib: https://matplotlib.org/  
Seaborn: https://seaborn.pydata.org/  
scikit-learn: https://scikit-learn.org/  
PyTorch: https://pytorch.org/


