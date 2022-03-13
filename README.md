# Computer-Vision-Rock-Paper-Scissors
In this lab, you will create an interactable Rock-Paper-Scissors game, in which the user can play with the computer using the camera.

THE GAME:
The rules follow the simple game of Rock, Paper, Scissors. The player holds their hand up to the camera displaying their choice, while the computer will display a random choice in the form of an emoji. Both chioces will be displayed on screen, along with the winner. This will repeat until a player reaches 3 points, and the game ends displaying the overall winner.

THE MODEL USED:
In order for the program to determine which chioce the player is displaying, the maching learning model, 'Teachable machine' was utilised. The model was trained with three options; Rock, Paper and Scissors. Increasing the size of the training set it was given may help with inconsistencies in detecting the correct choice. Tensorflow Keras model was downloaded. 

THE SET UP:
A virtual environment was first created for this project, this was done by first installing miniconda and then using conda to create and activate an environment, which I called "RPS_Env". Once in virutal studio code I opened my "project_1_dir" directory, created an .ipynb file and selected the python kernel "RPS_env".
Due to having an M1 mac, additional steps were required to successfully use the model and code. This required installing tensorflow, which is easily followed using the link: https://developer.apple.com/metal/tensorflow-plugin/

LIBRARIES USED:

Python 3 (3.8.12), OpenCV, Tensorflow, Numpy 


TO NOTE:
