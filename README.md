Real-Time Emotion Detection
This project uses the webcam to perform real-time emotion detection using the DeepFace library and OpenCV.

📸 Features
Real-time webcam feed

Face emotion analysis using DeepFace

Displays detected emotion on the video frame

Press q to quit the window

🛠 Requirements
Install the following Python libraries:

bash
Copy
Edit
pip install opencv-python
pip install deepface
You may also need to install other dependencies like tensorflow, keras, and mtcnn (automatically handled by deepface).

🚀 How to Run
Clone the repository or download the script.

Run the Python script:

bash
Copy
Edit
python main.py
A window will open showing the webcam feed with real-time detected emotion overlaid on the frame.

📁 File
main.py: The main script that captures video and analyzes emotion.

🧠 Emotion Detection Logic
Uses DeepFace.analyze() with actions=['emotion']

Displays the dominant emotion on the top-left of the video frame
