## Affinity Hackathon

In this challenge, we used data from ICBHI's 2017 Challenge, which includes 5.5 hours of recordings with 6898 respiratory cycles. Out of these, 1864 contain crackles, 886 contain wheezes, and 506 contain both crackles and wheezes, across 920 annotated audio samples from 126 subjects. We created machine learning models to classify respiratory diseases.

We utilized three different models: Tensorflow, Fast AI, and PYtorch. The Fast AI Model used a CNN model and mel spectrogram to classify patients as either healthy or having a respiratory disease. The Tensorflow model used MFCC features to train the model and predict the specific respiratory disease, while the PYtorch model used mel spectrogram features augmented by time and frequency masking to achieve the same objective.

Our Tensorflow model is particularly useful for classifying respiratory diseases.

## Acknowledgements

Datasets used
The data used in this challenge was obtained from the ICBHI 2017 Challenge. More information on this dataset can be found at `https://bhichallenge.med.auth.gr/ICBHI_2017_Challenge`.
