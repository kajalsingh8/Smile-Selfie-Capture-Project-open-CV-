Smile Selfie Capture Project
Overview
This project utilizes OpenCV to capture selfies when a smiling face is detected through your computer's webcam. The code uses Haar cascades for both face and smile detection to identify and locate faces and smiles in real-time video frames.

Dependencies
Python 3.x
OpenCV
Installation
Clone the repository to your local machine.

bash
Copy code
git clone https://github.com/your-username/smile-selfie-capture.git
cd smile-selfie-capture
Install the required dependencies.

bash
Copy code
pip install opencv-python
Download Haar cascades XML files for face and smile detection. You can find pre-trained models from OpenCV or other sources.

Update the file paths for the Haar cascade XML files in the code:

python
Copy code
faceCascade = cv2.CascadeClassifier("path/to/haarcascade_frontalface_default.xml")
smileCascade = cv2.CascadeClassifier("path/to/haarcascade_smile.xml")
Usage
Run the script.

bash
Copy code
python smile_selfie_capture.py
The live video window will open, and the program will capture selfies when it detects a smiling face.

Press 'q' to exit the program.

Notes
Make sure to have a stable webcam connection for optimal results.
Adjust the parameters for face and smile detection in the code if needed.
The captured selfies will be saved to the specified directory.
