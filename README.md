# custom_face_recognition

## Introduction
Detect and recognize faces with respect to the dataset provided. This project provides functionality for the user to add in their own and others images, and then recognize the same in a live video feed using OpenCV's `LBPHFaceRecognizer_create()`. The file `create_data.py` is used to create the dataset for the training of the recognizer, and the file `face_recognize.py` is used to recognize the faces in a live video feed and print the recognized face.

## How to use
- Clone the repository on your local machine.
- In the terminal, run the command `pip install -r requirements.txt`
- Open the file `create_data.py`, and on the 15th line, change the label to the name of the person you are creating the data for. Close the file, and then place yourself in front of the webcam of the computer in a well lit place, and then run the file. The program will then click a few photos and save it in the folder called `dataset`.
- Run the file `face_recognize.py` to test the trained recognizer. If everything works fine, you will find the name of the recognized individual being printed, with the prediction confidence.

Please revert and leave a comment for any suggestions or bugs in the file! 
Regards, Eric!
