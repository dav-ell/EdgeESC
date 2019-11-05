# EdgeESC
This repository contains the notebooks and data referenced in the paper Audio Classification at the Edge - LINK<br/>
This paper highlights our approach to classifying audio signatures in a recording by analyzing an audio signature's amplitude and MFCC. For a more in-depth explanation of how our model approaches this task we encourage you to read through the paper linked above.

# Data
The data used in our paper can be seen in the folder labeled "data". This folder houses six individual folders whose contents have been separate by sound classification. Each folder contains a variety of audio samples, some pulled from the ESC-50 dataset, the dcase2018 dataset, Youtube, as well as a selection of original contributions. Any additional audio samples that are added to these folders will be used to train the model at runtime.

# Install
To run the included notebooks you should first run the following command to install all necessary dependancies:
```
pip3 install -r requirements.txt
```

Our notebooks were developed with the following dependancies:
```
scipy==1.1.0
librosa==0.6.3
tqdm==4.28.1
Keras==2.2.4
numpy==1.15.4
tensorflow==1.13.1
scikit_learn==0.21.3
```

# Code
There are three individual notebooks for audio classification included in this repository; Amplitude, MFCC, and Ensemble. Amplitude classifies data based on the amplitude of the audio signature that it detects, MFCC (Mel-frequency cepstral coefficients) goes a few steps further than Amplitude, and Ensemble is a combination of the two. All three notebooks are fully functional and include the appropriate instructions per block of code. 

# Licensing Information
You'll find any relevant licensing information below:

ESC-50 dataset - (https://github.com/karolpiczak/ESC-50) - Refer to License/esc50_license.txt</br>
dcase2018 dataset - (https://github.com/DCASE-REPO/dcase2018_baseline) - Refer to License/dcase2018_license.csv</br>
Youtube clips - Refer to License/youtube_license.txt
