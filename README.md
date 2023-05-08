#Rock Paper Scissors Game with Hand Detection using OpenCV and Keras

This is a simple implementation of a rock paper scissors game in Python. The game uses hand detection to allow the player to make their choice, and a pre-trained Keras model to predict the computer's choice. The game is played through the camera of the user's device, and results are displayed on the screen.

##Getting Started

    Clone the repository to your local machine
    Make sure you have OpenCV and Keras installed on your machine
    Download the pre-trained Keras model from the repository (keras_model.h5)
    Run the game by typing python3 rspg.py in the terminal

##How to Play

    When the game starts, the message "ROCK, PAPER, SCISSORS!" will appear on the left side of the screen.
    Press the 's' key to start the game.
    When prompted, show your hand in the camera. The computer will predict its choice.
    Results will be displayed on the screen, and the message "Press 's' to move onto round X" will appear at the bottom of the screen. Press 's' to continue playing.
    The game will end after three rounds. Results of the game will be displayed on the screen.

##Notes

    If the camera cannot detect your hand, the message "The camera can't detect you. Press 's' to try again." will appear on the screen.
    The game is played in real-time, and the player only has 10 seconds to make their choice each round.
    The game can be restarted by typing 'python game.py' in the terminal.

##Authors

    Rexhino Rexhepi

##Acknowledgments

    This game was inspired by the popular rock paper scissors game, and uses OpenCV and Keras to implement hand detection and image recognition.
    Thanks to OpenCV and Keras for providing the necessary tools to create this game.