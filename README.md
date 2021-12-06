# Speech-Emotion-Recognotion

![image](https://user-images.githubusercontent.com/84785447/144185651-fb6ccb1e-f20e-4f5f-be1b-b97906c93218.png)

## Speech Emotion Recognition using the TESS dataset

2800 files from TESS. A set of 200 target words were spoken in the carrier phrase "Say the word _' by two actresses (aged 26 and 64 years) and recordings were made of the set portraying each of seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral). There are 2800 stimuli in total. Two actresses were recruited from the Toronto area. Both actresses speak English as their first language, are university educated, and have musical training. Audiometric testing indicated that both actresses have thresholds within the normal range.

## Audio Files:

Tested out the audio files by plotting out the waveform and a spectrogram to see the sample audio files.

## Waveform
![image](https://user-images.githubusercontent.com/84785447/144799830-dd57f31a-77dd-48c1-8663-b6959d2a3ce0.png)


## Spectogram
![image](https://user-images.githubusercontent.com/84785447/144799921-d7579b55-6348-4786-b259-087b564d0deb.png)


## Fetaure Extraction

The next step involves extracting the features from the audio files which will help our model learn between these audio files. For feature extraction we make use of the LibROSA library in python which is one of the libraries used for audio analysis.

![image 1](https://user-images.githubusercontent.com/84785447/144800297-12aa91ca-2a33-4f8b-90b9-f548dec1f78c.png)

## Building the model

![image 1](https://user-images.githubusercontent.com/84785447/144800583-116a305b-05db-470e-9518-87107008bea1.png)

## Result

![image 1](https://user-images.githubusercontent.com/84785447/144800884-2c57474d-a4ef-4f7e-90dd-f74d81a679ee.png)

![image 1](https://user-images.githubusercontent.com/84785447/144801056-288b47b0-6d3d-4a43-9c70-495e0b024e21.png)

## Testing the model

![image 1](https://user-images.githubusercontent.com/84785447/144801370-20014c00-a69f-43cf-95fb-81706e57325c.png)

## Prediction made by the model

![image 1](https://user-images.githubusercontent.com/84785447/144801904-b71c3eb8-08a9-448a-a3e9-5d7f047d03cc.png)

## Conclusions

Building the model was a challenging task as it involved lot of trail and error methods, tuning etc. The model is very well trained to distinguish between male and female voices and it distinguishes with 100% accuracy. The model was tuned to detect emotions with more than 80% accuracy. Accuracy can be increased by including more audio files for training.


