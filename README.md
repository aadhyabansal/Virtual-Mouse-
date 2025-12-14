# Virtual-Mouse
This project implements a **Virtual Mouse system** that allows users to control mouse movements and clicks using **hand gestures**, without touching a physical mouse. It uses computer vision techniques and external Python libraries to track hand landmarks in real time through a webcam.
##  Features
- Control mouse cursor using hand movement.
- Perform actions like left click, right click, double click, and screenshot using finger gestures.
- Real-time hand tracking using webcam.
- Touchless and intuitive user interaction.

##  Tech Stack & Libraries
- Python  
- OpenCV  
- MediaPipe  
- PyAutoGUI  
- NumPy

> The entire implementation is done in a **Jupyter Notebook (.ipynb)**.

## How It Works
- Webcam captures live video feed.
- Hand landmarks are detected using MediaPipe.  
- Finger positions are mapped to screen coordinates.  
- Mouse movement and clicks are simulated using PyAutoGUI.

## Project Structure
```text
Virtual-Mouse/
│
├── Virtual_Mouse.ipynb   
├── util.py               
├── .gitignore            
├── README.md

```
## How to Run

 Clone the repository
 
	git clone https://github.com/aadhyabansal/Virtual-Mouse-.git


 Install required libraries

	pip install opencv-python mediapipe pyautogui numpy


 Open the Jupyter Notebook

	jupyter notebook


 Run Virtual_Mouse.ipynb and allow webcam access
