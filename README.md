### Author: Nazarii Kuspys

### Exploring ways to represent a audio data for classification tasks (on the example of Urban8k classification problem)

Before proceeding, author was inspired by this course - https://github.com/maziarraissi/Applied-Deep-Learning

If you want to get some knowledge about these ideas, before continuing with my work, you can try to watch:

https://www.youtube.com/watch?v=hF72sY70_IQ - briefly about theory of notions and ideas, which were implemented in this notebook.

Also, some papers, that can be useful for readers: https://towardsdatascience.com/learning-from-audio-the-mel-scale-mel-spectrograms-and-mel-frequency-cepstral-coefficients-f5752b6324a8

2021 paper explores the problem of audio representation (MFCC vs Mel Spectrogram) for Automatic speaker verification: https://arxiv.org/pdf/2102.10322.pdf

another 2021 paper with the similar research task (A COMPARISON OF AUDIO SIGNAL PREPROCESSING METHODS FOR DEEP NEURAL NETWORKS ON MUSIC TAGGING) https://arxiv.org/pdf/1709.01922.pdf

### There are mainly 5 different ways to represent sound data:

1. Raw data (extracted signal from wav or mp3 file)

2. STFT - Short-time Fourier transform of signal

3. Mel-spaced Filterbank

4. Mel Spectrogram

5. MFCC coefficients (obtained after gaining Mel Spectrogram using Discrete Cosine Transform)
In this work I focus on MFCC vs Mel Spectrogram data representation

So, without further ado, Let's proceed with notebook!
