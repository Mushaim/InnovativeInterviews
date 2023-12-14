
# Innovative Interviews - Emotion Recognition and Analysis

Innovative Interviews is a project that combines facial emotion recognition, eye position tracking, face position analysis, and audio transcribing to provide a comprehensive analysis of interviews or presentations. The project utilizes computer vision, deep learning, and audio processing techniques to assess the interviewee's emotional state, eye positions, face orientation, and speech disfluencies.

## Features

- **Facial Emotion Recognition**: Utilizes a pre-trained MobileNetV2 model for recognizing emotions (Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral) from facial expressions.

- **Eye Position Tracking**: Monitors the position of the eyes (left, center, right; top, middle, bottom) to evaluate the interviewee's gaze.

- **Face Position Analysis**: Assesses the orientation of the face (left, right, top, bottom, forward) using facial landmarks to understand the interviewee's head movement.

- **Audio Transcribing and Disfluency Counting**: Transcribes audio from the video and counts speech disfluencies, providing insights into the speaker's communication style.

- **Overall Confidence Level Calculation**: Combines the confidence levels from facial emotions, eye positions, face orientation, and speech disfluencies to provide an overall assessment.

## Getting Started

**Prerequisites**: Ensure you have the necessary dependencies installed by running:

   ```bash
   pip install -r requirements.txt
   ```
 #### Training
The Emotion Recognition Model (Optional): If you want to retrain the emotion recognition model, follow the instructions in the model training section of the code.
#### Running the Code
Instead of "video.mp4" in cell 14, write the path to your input video. Then run all the cells in their order.
#### Output: 
The program will output annotated video frames and provide a comprehensive confidence level assessment. 

### Project Structure

confidenceUsingModel.ipynb: The main script that processes video frames, performs emotion recognition, eye tracking, face orientation analysis, and audio transcribing.

my_model.h5: Defines the emotion recognition model architecture and loads pre-trained weights.

data: Download the dataset [FER-13](https://www.kaggle.com/datasets/msambare/fer2013).

train/ and validation/: Replace the following paths with the location where you have downloaded the 'train' and 'validation' folders from the dataset in cell 3.

Datadirectory = "path/to/your/downloaded/train/"
Validationdirectory = "path/to/your/downloaded/validation/"

## Dependencies


- [![Python 3.x](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
- [![matplotlib](https://img.shields.io/badge/matplotlib-latest-blue.svg)](https://matplotlib.org/)
- [![NumPy](https://img.shields.io/badge/NumPy-latest-blue.svg)](https://numpy.org/)
- [![OpenCV](https://img.shields.io/badge/OpenCV-latest-blue.svg)](https://opencv.org/)
- [![TensorFlow](https://img.shields.io/badge/TensorFlow-latest-blue.svg)](https://www.tensorflow.org/)
- [![moviepy](https://img.shields.io/badge/moviepy-latest-blue.svg)](https://zulko.github.io/moviepy/)
- [![whisper_timestamped](https://img.shields.io/badge/whisper_timestamped-latest-blue.svg)](https://github.com/linto-ai/whisper-timestamped)
- [![keyboard](https://img.shields.io/badge/keyboard-latest-blue.svg)](https://github.com/boppreh/keyboard)
- [![mediapipe](https://img.shields.io/badge/mediapipe-latest-blue.svg)](https://mediapipe.dev/)

### Acknowledgments
- [MobileNetV2]()
- [haarcascade_frontalface_default](https://github.com/kipr/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml5)
- [Mediapipe](https://developers.google.com/mediapipe)
- [Whisper](https://openai.com/research/whisper)


### Contact

Mushaim Khan

Email: mushaimk01@gmail.com

Amena Shahid

Email: amenashahid58@gmail.com
