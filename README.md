# Sign-Language-To-Text-Conversion

# Abstract

Sign language is one of the oldest and most natural form of language for communication, but since most people do not know sign language and interpreters are very difficult to come by we have come up with a real time method using neural networks for fingerspelling based american sign language.

In this method, the hand is first passed through a filter and after the filter is applied the hand is passed through a classifier which predicts the class of the hand gestures. This method provides 98.00 % accuracy for the 26 letters of the alphabet.

# Project Description

American sign language is a predominant sign language Since the only disability D&M people have is communication related and they cannot use spoken languages hence the only way for them to communicate is through sign language.

Communication is the process of exchange of thoughts and messages in various ways such as speech, signals, behavior and visuals.

Deaf and Mute(Dumb)(D&M) people make use of their hands to express different gestures to express their ideas with other people.

Gestures are the nonverbally exchanged messages and these gestures are understood with vision. This nonverbal communication of deaf and dumb people is called sign language.

Sign language is a visual language and consists of 3 major components

- Finger Spelling : Used to spell words letter by letter
- Word level Vocabulary : Used for the majority of communication
- Non-Manual features : Facial Expressions like mouth, tongue and body positions

In this project I basically focus on producing a model which can recognize Fingerspelling based hand gestures in order to form a complete word by combining each gesture.

The gestures I trained are as given in the image below.

![ss](https://user-images.githubusercontent.com/94343636/207827546-0c2edc00-7169-4db2-9a09-288f6710292a.jpg)

# Steps of Building this Project

- The first Step of building this project was of creating the folders for storing the training and testing data. As, in this project I have built my own dataset.
- The second step, after the folder creation is of creating the training and testing dataset.
- After the creation of the training and testing data. The third step is of creating a model for training. Here, I have used Convolutional Neural Network(CNN) for building this model.
- The final step after the model has been trained is of creating a GUI that will be used to convert Sings into text and form sentence, which would be helpful for communicating with D&M people.

# Libraries Requirements -(Requires the latest pip version to install all the packages)

'''
1. Lastest pip -> pip install --upgrade pip

2. numpy -> pip install numpy

3. string -> pip install strings

4. os-sys -> pip install os-sys

5. opencv -> pip install opencv-python

6. tensorFlow -> i) pip install tensorflow 
                 ii) pip3 install --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.8.0-cp34-cp34m-linux_x86_64.whl

7. keras -> pip install keras

8. tkinter -> pip install tk

9. PIL -> pip install Pillow

10. enchant -> pip install pyenchant (Python bindings for the Enchant spellchecking system)

11. hunspell -> pip install cyhunspell (A wrapper on hunspell for use in Python)
'''

