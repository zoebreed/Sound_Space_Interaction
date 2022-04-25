# Pure Dance
###### By Zoë Breed and Joyce den Hertog
An interactive sound experience that generates sound on the basis of the user's position in space and the movements and angles of their arms and legs. Developed using Pure Data and [MediaPipe](https://google.github.io/mediapipe/getting_started/python.html) in Python.

## Instructions
1. Make sure you have enough space to move around, such that your webcam is able to record your full body, and there should be no one else in the frame. 
2. Make sure you have Python and Pure Data installed.
3. Install the following libraries/externals:
    - Python pip libraries:
       - [mediapipe](https://pypi.org/project/mediapipe/) (NOTE: this library might not work on Mac M1 chips, the workaround from the top comment in [this](https://stackoverflow.com/questions/68659865/cannot-pip-install-mediapipe-on-macos-m1) post might help out). 
       - [opencv-python](https://pypi.org/project/opencv-python/)
       - [python-osc](https://pypi.org/project/python-osc/)
    - PureData externals:
       - [cyclone](https://github.com/porres/pd-cyclone)
4. Open `main.pd` and press the start toggle in the upper left corner to turn on the sound. 
5. Run PoseNet by running `python code/python_posenet/send_poses.py` from the terminal. 
6. You should see something like this: 

![PoseNet-gif](https://s7.gifyu.com/images/ezgif.com-gif-maker1ddcd309221623e73.gif) 

#### Have fun dancing! 
