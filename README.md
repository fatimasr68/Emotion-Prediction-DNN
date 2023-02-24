
## Deep Learning Model for Emotion Recognition via fMRI-Drived Brain Data

The Long Short-Term Memory (LSTM) neural network was applied to fMRI-derived beta-series matrices of dimension 90*37130 corresponding to 90 stimuli and 37130 gray-matter voxels to predict the normative valence and arousal scores (in 9-point Likert scale) of affective stimuli.
The model also used as a classifier to classify each stimulus responses into two categories: high/low arousal and positive/negative valence.  


## Long Short-Term Memory (LSTM) Networks 
Long Short-Term Memory (LSTM) networks are a type of recurrent neural network that are used in this project to process the fMRI driven brain data. They are able to remember information over long periods of time, making them well suited for this task. 

## Prediction
The LSTM model was used to predict the normative valence and arousal scores (in ۹-point Likert scale) of affective stimuli. The predictions were evaluated using Pearson correlation coefficient between the predicted scores and the ground truth scores.

## Classification
The LSTM model was also used as a classifier to classify each stimulus responses into two categories: high/low arousal and positive/negative valence. The classification accuracy was evaluated using F1 score, precision and accuracy metrics.

## Conclusion 
The results of this study suggest that, given sufficient data, deep learning is a viable option for emotion recognition as features can be learned directly from raw data. Specifically, achieves higher average accuracy over subjects compared to other traditional methods.

Results show that the model can accurately predict and classify emotions from fMRI scans with an accuracy of up to 80%.
