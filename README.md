OpenCV Game: Avoid Falling Squares with Your Head

This is a mini-game project in Python using OpenCV.
Main idea:

    Squares fall from the top of the screen.
    Your head (detected by the camera) must avoid these squares.
    The score increases each time a square is successfully avoided.

Features

    Face detection: uses a Haar Cascade classifier (haarcascade_frontalface_default.xml).
    Real-time display: uses the webcam with cv.VideoCapture.
    Obstacles: squares are randomly generated and fall at an adjustable speed.
    Scoring: the score increments when a square exits the screen without colliding with your head.
    Game Over: if a square collides with your head, the game ends and restarts automatically.
