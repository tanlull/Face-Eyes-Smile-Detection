# Play Chrome hidden Dinosaur game with smiling

[//]: # (References)
[no-smile]: ./imgs/screenshot-0.jpeg
[smile]: ./imgs/screenshot-1.jpeg
[opencv]: https://opencv.org/
[installation]: #installation-of-opencv
[haar-like-features]: https://www.quora.com/How-can-I-understand-Haar-like-feature-for-face-detection
[win-open-cv-wheel]: https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv

---

## Detection of faces, eyes, and smiles
This project uses [Haar-like features][haar-like-features] to detect faces, eyes, and smiles. It is done in Python 3.6 and uses the open source computer vision library [OpenCV][opencv]. To install OpenCV for Python please follow the [installation process below][installation].

By executing the script the internal webcam gets started and draws blue rectangles around faces, green rectangles around eyes and red rectangles around smiling mouths in the webcam video stream.

Face and eyes detection only       |  Face, eyes and smile detection
:---------------------------------:|:---------------------------------:
![no-smile][no-smile]              | ![smile][smile]

## Installation of OpenCV , pyautogui
To install the OpenCV library for Python execute the following line in a terminal/command window:
```sh
pip install -r requirements.txt
```
## Run
1. Disconnect the internet or Wifi from your computer.
2. Open Chrome Browser, you will see the "No Internet" error page.  
3. Go to terminal and Run 
```sh
python smile_detection.py
```
4. Go back to browser
5. Let SMILE !