# Emotion Recognition from Speech Model 
# Overview
This project uses a deep learning model to recognize emotions in speech. The model classifies speech into emotions like happiness, anger, and sadness using deep learning techniques and speech processing.
# Usage
To use the credit scoring model, follow these steps:

Ensure you have Python installed on your machine.
Open the Jupyter notebook credit_score.ipynb.
Follow the instructions provided in the notebook to load the dataset, preprocess the data, train the classification models, and assess their accuracies.
Experiment with different algorithms and parameters to optimize the model performance.

# Dataset 
The dataset includes recordings of two actresses (aged 26 and 64) speaking 200 target words in a phrase, "Say the word _," expressing seven emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral. There are 2800 audio files in WAV format.

Dataset is too large to be included here. You can download it from the link below:

Download Dataset :- https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess
If dataset  is not download then you can connect with me.

The dataset includes audio recordings labeled with different emotions. Commonly used datasets include:
RAVDESS (The Ryerson Audio-Visual Database of Emotional Speech and Song)
EMO-DB (Berlin Database of Emotional Speech)

# Output
The model classifies audio into these emotions:

Anger
Disgust
Fear
Happiness
Pleasant Surprise
Sadness

# Technologies Used
Python
Librosa (for audio processing)
TensorFlow/Keras (for deep learning)
Scikit-learn (for machine learning)
Matplotlib/Seaborn (for visualization)

# Results
The accuracies of different classification models are as follows:

Logistic Regression: 69.6%
K-Nearest Neighbors (KNN): 89.7%
Random Forest: 96%

# License
This project is licensed under the MIT License.
