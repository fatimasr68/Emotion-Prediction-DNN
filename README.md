
# Deep Learning Model for Emotion Recognition via fMRI-Drived Brain Data

Long Short-Term Memory (LSTM) neural network was applied to fMRI-derived beta-series matrices of dimension 90*37130 corresponding to 90 stimuli and 37130 gray-matter voxels to predict the normative valence and arousal scores (in 9-point Likert scale) of affective stimuli. The model also used as a classifier to classify each stimulus responses into two categories: high/low arousal and positive/negative valence.  


## Long Short-Term Memory (LSTM) Networks 
Long Short-Term Memory (LSTM) networks are a type of recurrent neural network that are used in this project to process the fMRI driven brain data. They are able to remember information over long periods of time, making them well suited for this task. 

## Prediction
The LSTM model was used to predict the normative valence and arousal scores (in ۹-point Likert scale) of affective stimuli. The predictions were evaluated using Pearson correlation coefficient between the predicted scores and the ground truth scores.

## Classification
The LSTM model was also used as a classifier to classify each stimulus responses into two categories: high/low arousal and positive/negative valence. The classification accuracy was evaluated using F1 score, precision, recall, and accuracy metrics.

## Conclusion 
This project is focused on developing a deep learning model for emotion recognition from fMRI driven brain data. The model will use Long Short-Term Memory (LSTM) networks, and prediction and classification algorithms to accurately identify emotions from brain fMRI data.
