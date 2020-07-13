# Speech Chess 

A Python script written in Jupyter notebook to take input commands in the form of speech to play Chess!

## Prerequisites

For running this script you'll need:
* Jupyter Notebook
* SpeechRecognition Module
* PyAudio Module
* Chess Module
* PiP Installer
* An active internet connection *as Google API needs internet to function*

## Installing

If you have Python up and running all you need to do is download the external modules from the PiP Installer, just type:
```pip install SpeechRecognition```
```pip install PyAudio```

You will also require ```python-chesss``` module, for that:
```pip install python-chess```
After this, you'll be ready to code!

**P.S:** If you are **unable to open the code from the given Jupyter noebook file**, click [here.](https://colab.research.google.com/drive/1CZI1nQHwf4-eMNQ_YTjm_w569ld8HUkI?usp=sharing)

## Input and Output

Speak your desired moves, first the intiial block, followed by the final block. A matrix of chess board is also printed on the console screen for the ease of the user.
Any illegal move or a wrong speech input will require to give the speech command again. 
All the moves you make will be represented on the GUI board *(opens in a separate window)*

## Built With 

* Python
* Google Speech-to-Text API 

**Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/kg1510/)**
