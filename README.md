# Speech-Emotion-Recognition

Using a Convolutional Neural Network to train the RAVDESS dataset for speech emotion recognition.

<br>

## Background
The experiment uses the librosa library to parse the audio. Librosa is a Python library for analyzing audio and music, with a flatter layout, standardized interfaces and names, backward compatibility, modular functions, and readable code. The experiment aims to build a model to recognize emotion in speech using librosa and sklearn libraries and the RAVDESS dataset. The RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset is an audio-visual database of emotional speech, which contains 1440 files, and 24 people (12 males, 12 females) conducted 10 tests on emotional validity, intensity and authenticity. ratings. The entire dataset is 24.8GB from 24 actors and can be downloaded from the link below in ***Dataset***. Actors spoke two lexically matched statements using a neutral North American accent, and verbal emotions included expressions of calm, happiness, sadness, anger, fear, surprise, and disgust. Each expression is classified into three emotional intensities, normal, strong and neutral.

<br>

## Dataset
Speech Emotion Recognition RAVDESS Dataset

Link: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio

<br>

## Audio and Waveplot Display

|                         Female Angry                         |                           Male Sad                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![image-20230105180852999](README/image-20230105180852999.png) | ![image-20230105180936489](README/image-20230105180936489.png) |

<br>

## Mel Spectrogram

|                         Female Angry                         |                           Male Sad                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![image-20230105181242569](README/image-20230105181242569.png) | ![image-20230105181224322](README/image-20230105181224322.png) |

<br>

## One-Hot Encoder

| Label                                                        | One-Hot Encoder                                              |
| :------------------------------------------------------------: | :------------------------------------------------------------: |
| ![image-20230105192956412](README/image-20230105192956412.png) | ![image-20230105193016938](README/image-20230105193016938.png) |

<br>

## Result

| ![image-20230105195922828](README/image-20230105195922828.png) |
| ------------------------------------------------------------ |

<br>

| ![image-20230105200551265](README/image-20230105200551265.png) | ![image-20230105200555409](README/image-20230105200555409.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

<br>

| ![image-20230105220845419](README/image-20230105220845419.png) |
| ------------------------------------------------------------ |

<br>

| ![image-20230105200948958](README/image-20230105200948958.png) |
| ------------------------------------------------------------ |

