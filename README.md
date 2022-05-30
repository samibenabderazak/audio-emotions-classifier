# audio-emotions-classifier
This is an audio emotions classifier
It classifies audio files by emotions and gender:

#### Datasetes used:  
CREMA-D: https://www.kaggle.com/ejlok1/cremad/code  
TESS: https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess/kernels  
RAVDESS: https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio  
SAVEE: https://www.kaggle.com/ejlok1/surrey-audiovisual-expressed-emotion-savee


First the machine learning model is trained in 1D CNN, then in 2D CNN.
in 1D CNN we got an accuracy for gender classification of about 81%. 
For emotions classification 54% accuracy.
For combined emotions and gender classification: 48%.

As the accuracy percentage was low in 1D CNN, I made it into 2D CNN and in the end managed to get an accuracy of 66% for combined genders and emotions classification.

#### Classes used in this model training:  
Gender classes:  
Male, female.  

Emotions classes:  
Angry, fear, happy, sad, surprise, neutral, disgust.  

Combiend emotions and genders classes:  
female_angry, female_disgust, female_fear, female_happy, female_sad, female_surprise, female_neutral, 
male_angry, male_fear, male_happ, male_sad, male_surprise, male_neutral, male_disgust.  

#### Results:  

1D CNN genders classification result:  
![image](https://user-images.githubusercontent.com/23135398/139412787-7a04f986-47ae-4f62-90f6-a5e914c697f6.png)

1D CNN emotions classification result:  
![image](https://user-images.githubusercontent.com/23135398/139412964-3a10d0d9-e272-40d8-8637-181d74504d95.png)

1D CNN combined genders and emotions classification result:  
![image](https://user-images.githubusercontent.com/23135398/139414917-17a4b73e-86b9-49bc-aaea-9ea13186dde7.png)

Final result, 2D CNN combined genders and emotions classification:
![image](https://user-images.githubusercontent.com/23135398/139415112-a076a7b9-1ed4-4cd6-bc10-7dc86c97fb93.png)

Sources for this project:
https://www.kaggle.com/ejlok1/audio-emotion-part-1-explore-data
