Senty Player is an innovative application that captures the user's mood in real-time using advanced computer vision and deep learning techniques to suggest personalized music recommendations. By utilizing a comprehensive tech stack, the project achieves a seamless and interactive user experience.

Working of the website: https://youtu.be/GpzyzxWPe-M

Key Technologies:

MediaPipe: Employed for real-time face and hand landmark detection to analyze user expressions and gestures.

OpenCV: Used for video processing and capturing live data from the webcam.

TensorFlow & Keras: Built and trained a deep learning model to predict the user's mood based on the detected landmarks.

NumPy: Handled numerical operations and processed landmark data efficiently

Streamlit: Created an interactive web interface for user interaction.

Streamlit-WebRTC: Integrated webcam video streams directly into the Streamlit interface.

AV: Processed video frames within the Streamlit environment.

Steps:

Train the models
Create a virtual environment python -m venv venv --> venv\Scripts\activate --> pip install -r requirements.txt
To run the project: cd Test --> streamlit run player.py
