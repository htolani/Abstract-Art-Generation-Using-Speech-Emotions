# Abstract-Art-Generation-Using-Speech-Emotions

<h2>Abstract Art Generation Using Speech Emotions</h2>

Application to analyse user speech emotion based on which we will generate an image in the form of artwork.

<b>Methodology:</b>

<img src="https://github.com/htolani/Abstract-Art-Generation-Using-Speech-Emotions/blob/main/System%20Architecture.png" width="850" height="450">

<b><a href="https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio">Data Set Link</a>:</b>
https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio


<b>Pre-requisites:</b>
To run the code, we need to follow these steps:
• Run the cell which installs the libraries (Cell 1)
• Run the cell which imports the libraries and performs some basic configurations (Cell 2)
• Run the cells which define the necessary helper and training functions for VQGAN+CLIP (Cells 3, 4, 5, 6 and 7)
• Run the cells which defined methods for extracting features from the audio file and loading the dataset(Cells 8, 9 and 11)
• We will skip the cells which train the models, since they are already trained and will run the 2nd last and the last cell.
• Speak for 3 seconds after pressing ENTER on the prompt.
• The speech will be converted to text and emotions and an image will be generated after 300 interations.
