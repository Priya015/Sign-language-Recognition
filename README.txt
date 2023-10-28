## Sign Language Recognition using CNN
Communication is very significant to human beings as it facilitates the spread of knowledge and forms relationships between people.We use a variety of communication techniques, such as voice, writing, drawing, reading, and using our hands to sign. But the most often utilised form of communication is speech.Those who are deaf or hard of hearing rely mostly on nonverbal means of communication since they are unable to talk or hear and must communicate through signals. Nearly five million individuals in the large nation of India are deaf or hard of hearing. Due to the complexity of this field, relatively little study has been done in it to yet.With around five million deaf and hard of hearing citizens, India is a large nation. Because this research topic is so difficult, relatively little work has been done in it thus far. The term Indo-Pakistani Sign Language (IPSL) is also often used to refer to Indian Sign Language (ISL), which is mostly utilised in South Asian nations.

The purpose of this project is to recognize all the alphabets (A-Z) and digits (0-9) of Indian sign language using bag of visual words model and convert them to text/speech.

Pre-requisites
Before running this project, make sure you have following dependencies -

## Technologies and Tools
* Python 
* TensorFlow
* Keras
* OpenCV

## CNN Model
The model consist of : Three convolution layer each followed bt MaxPooling for better feature capture A dense layer of 512 units The output layer with 24 units for 24 different classes

Convolution layers Conv layer 1 -- UNITS - 128 KERNEL SIZE - 5 * 5 STRIDE LENGTH - 1 ACTIVATION - ReLu
Conv layer 2 -- UNITS - 64 KERNEL SIZE - 3 * 3 STRIDE LENGTH - 1 ACTIVATION - ReLu
Conv layer 3 -- UNITS - 32 KERNEL SIZE - 2 * 2 STRIDE LENGTH - 1 ACTIVATION - ReLu
MaxPool layer 1 -- MAX POOL WINDOW - 3 * 3 STRIDE - 2
MaxPool layer 2 -- MAX POOL WINDOW - 2 * 2 STRIDE - 2
MaxPool layer 3 -- MAX POOL WINDOW - 2 * 2 STRIDE - 2

## Features
Our model was able to predict the characters in the ASL with a prediction accuracy >90%.

## Status
Project is: _finished_

## Contact
Created by me with my teammate. [Priya Lokhande](https://github.com/Priya015),[Aditi Burud](https://github.com/aditiburud36).

