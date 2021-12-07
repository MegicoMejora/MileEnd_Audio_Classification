# MileEnd_Audio_Classification
## MileEnd Spoken Numerals classification using Macine Learning

The major parts of the projects are,
  1. Data Creation
  2. Building the Classifier model that classifies the intonation of short audio clips using the Mile End Spoken Numerals.

## Data Creation

Dataset was developed by the School of Electonics Engineering & Computer Science of the Queen Mary University of London. Roughly 185 postgraduate students contributed wth audio clips. Audio clips were further separated, cleaned and published by the team led by Dr. Jesus Requena-Carrion. Audio clips contain different numbers spoken by students in different intonations viz. Excited, Bored, Question and Neutral.

Dataset URL: https://collect.qmul.ac.uk/down?t=4LO0R0TSLPGGHJPC/45O137K56GGVDFUT9AH4ST0

## Model Building

Steps involved in the model building such as dataset preprocessing, feature exrtaction, model training, validation and testing are explained in the notebook: 

### Feature Extraction

These are the features extracted from the audio clips.

1.Power

2.Pitch mean

3.Pitch standard deviation

4.Fraction of voiced region

5.Spectral Centroid

6.Spectral Bandwidth

7.Spectral RollOff

8.Zero Crossing Rate
9.Chroma STFT
10.MelSpectrogram


Logistic Regression Classifier
Support Vector Machines(SVM)
SVM with normalized values and tuned parameters using grid search
KNN classifier
