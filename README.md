# Crowd_emotion_detection
Abstract:
Crowd Emotion Recognition (CER) identifies collective emotions from crowd sounds using AI. This involves analyzing noises like cheering and booing to gauge the crowd's emotional state. Despite advancements, current methods often struggle with accuracy. Our project uses Convolutional Neural Networks (CNNs) to improve upon existing models.

Keywords: Speech Recognition, Convolutional Neural Networks, Mel-spectrograms, Deep Learning, Machine Learning

1. Introduction:
Studying crowd emotion can enhance safety and security by predicting behavior based on acoustic features. Despite various approaches and tools, challenges remain in accuracy and efficiency.
  1.1 Literature Review:
  Recent studies show varying accuracies with algorithms like SVM, KNN, and Decision Trees. Our CNN model outperforms these with higher accuracy and better efficiency.

3. Research Gap:
Existing models vary in accuracy and efficiency. Our approach aims to address these issues by using feature-based spectrograms and numerical data representation to improve performance and reduce processing time.

Methodology:

1. Data Acquisition: Normalized audio files categorized into approved, disapproved, and neutral, with Mel spectrograms used for frequency representation.
2. Data Preprocessing: Utilized libraries like Pydub, AudioSegment, Glob, librosa, Pandas, and Numpy for processing and feature extraction.
3. Feature Extraction: Employed methods like Mel-Frequency Cepstral Coefficients (MFCC), Complex Short-Time Fourier Transform (C STFT), Complex Constant-Q Transform (C CQT), and Complex Cepstral Envelope Normalization Spectrum (C CENS).
4. Model Training: Implemented CNN with preprocessing, architecture design, one-hot encoding, and tested with various epochs. LSTM was also tested but CNN showed superior performance with 96.53% accuracy.

Results and Discussion:

4.1 Result Analysis: CNN achieved 96.53% accuracy, with each run taking 1 minute 3 seconds and optimal epoch value of 50.
4.2 Visualization: Training & loss graph and accuracy metrics.
5. Conclusion:
Our CNN model for CER uses advanced feature extraction techniques and libraries for improved emotion recognition from crowd sounds. The approach enhances accuracy and processing efficiency compared to traditional methods.
