# Fake News Detection with LSTM

## Overview
This repository contains a deep learning workflow for fake news detection using an LSTM model.  
The project demonstrates how sequence modeling can classify news articles as fake or real.

##[Live Demo](https://youtu.be/Mv7T_Dird6s)

## Dataset
- Source: Combined `Fake.csv` and `True.csv`.
- Columns: `title`, `text`, `subject`, `date`.
- Labels: `0 = Fake`, `1 = Real`.
- Kaggle dataset : https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets

## Notebook Contents
- **Data Preparation:** Merge datasets, clean text, create labels.
- **Tokenization & Padding:** Convert text into sequences for LSTM.
- **Model:** LSTM with embeddings, dropout, and EarlyStopping.
- **Evaluation:** Accuracy, F1 score, confusion matrix, ROC curve.
- **Visualization:** Training vs validation curves.

## Results
- Accuracy: ~93%  
- F1 Score: ~0.92  
- AUC: ~0.94  

## How to Run
1. Open the notebook in Google Colab.
2. Upload the dataset (`Fake.csv`, `True.csv`).
3. Run cells sequentially to reproduce results.

## Tools i used
Python, TensorFlow/Keras, Scikit‑Learn, Matplotlib, Seaborn.

## Future Work
- Experiment with bidirectional LSTMs.
- Compare with GRU models.
- Deploy as a Streamlit app for interactive testing.

- ## 👩‍💻 Author

*Zahabia Ahmed*  
Data Science Learner | Educator | Content Creator | Aspiring AI Engineer 
[YouTube: Zahabia Ahmed](https://www.youtube.com/@ZahabiaAhmed)
[Instagram](https://www.instagram.com/zahabiaahmed?igsh=MXkwNzkzdGJsMzJqOA==)
[FaceBook](https://www.facebook.com/share/1KBwSz91no/)
[X- Twitter]( https://x.com/AhmedZahabia?t=yAAjSTYTwRRQsXCeomBMuQ&s=08)
[Pinterest](https://pin.it/47OMFKosD)

**Always Feel Free to contact me . Be Happy, Keep Coding**
