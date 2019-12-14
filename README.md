# Emotion-Recognition
Part of Time series course Fall 2019 at NYU

In this work, we conduct an extensive comparison of various approaches to speech based emotion recognition systems. The analyses were carried out on audio recordings from Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS). After pre-processing the raw audio files, features such as Log-Mel Spectrogram, Mel-Frequency Cepstral Coefficients (MFCCs), pitch and energy were considered.  The significance of these features for emotion classification was compared by applying methods such as Long Short Term Memory (LSTM), Convolutional Neural Networks (CNNs), Hidden Markov Models (HMMs) and Deep Neural Networks (DNNs). On the 14-class (2 genders * 7 emotions) classification task, an accuracy of 66%  was achieved with a 4-layer 2 dimensional CNN using the Log-Mel Spectrogram features. We also observe that, in  emotion recognition, the choice of audio features impacts the results much more than the model complexity.

We have included jupyter notebooks for various feature engineering and deep learning methods that we applied towards this problem. Please refer to our report for detailed explanantions.

We used the codes from https://github.com/rezachu/emotion_recognition_cnn for data pre-processing.
