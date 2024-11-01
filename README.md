
# FaceVibe - Real-Time Emotion Detection

This project is a real-time emotion detection application that uses a pre-trained deep learning model to recognize emotions through facial expressions captured on live video. Built with Flask, OpenCV, and Keras, the application identifies and displays emotions in real time, making it ideal for interactive interfaces, user experience research, and various real-time monitoring applications.

### Key Features
- Real-Time Emotion Detection: Utilizes the webcam to capture and classify emotions on live video feeds.
- Flask Web Application: The application serves as a web app with a live video feed viewable directly in the browser.
- Emotion Classification: Identifies emotions like Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.
- Face Detection with OpenCV: Detects and isolates faces within each video frame to focus emotion analysis only on the facial region.
- User-Friendly Interface: The live video feed in the browser displays real-time emotion predictions, overlaid with the detected emotion label.

### How It Works
- Face Detection: Each frame from the webcam feed is processed to detect faces using OpenCV’s Haar Cascade classifier.
- Emotion Prediction: Detected facial regions are resized and preprocessed, then fed into a pre-trained Keras model for emotion prediction.
- Display Emotion: The predicted emotion label is displayed on top of each detected face in the live video stream.
- Web Interface: The Flask application serves the real-time video feed with emotions displayed, accessible through a web browser.

### Installation
1. Clone the repository
   ```sh
   git clone https://github.com/letsdoitbycode/FaceVibe.git
   cd FaceVibe
   ```

3. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```sh
   pip install requirements.txt
   ```
   
4. Run the Flask app:
    ```sh
    python app.py
    ```

### Project Structure
```plaintext
YouTube-Video-Summarization-App/
│
├── app.py                                              # Main Flask application
├── templates/
│   └── index.html                                      # Main HTML file
├── static/
│   ├── style.css                                       # CSS styles
├── emotion-classification-cnn-using-keras.ipynb        # Script to define and train the CNN model.
├── haarcascade_frontalface_default.xml                 # Pre-trained Haar Cascade classifier for face detection.
├── model.h5                                            # Pre-trained CNN model for emotion detection.
├── requirements.txt                                    # requirements for the project
└── README.md                                           # This README file
```

## Demo Application Interface
![Screenshot 2024-11-01 163047](https://github.com/user-attachments/assets/2c54f20e-0464-421d-a768-fbbfdd47bc3f)



## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.




