# Face Emotion Detection

This is a deep learning-based face emotion detection system using OpenCV and a Convolutional Neural Network (CNN) trained on facial expressions.

## Features
- Detects faces in real-time using OpenCV
- Classifies facial emotions into categories: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
- Uses a pre-trained model for prediction
- Runs on live webcam feed

## Project Structure
```
├── datasets/
│   ├── model.json
│   ├── bestmodel.h5
│   ├── haarcascade_frontalface_default.xml
├── app.py
├── requirements.txt
├── README.md
```

## Installation
### Prerequisites
- Python 3.x
- OpenCV
- TensorFlow & Keras
- NumPy
- Matplotlib
- Pandas
- scikit-learn

### Setup
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   python app.py
   ```

## Model Details
- The model is a CNN trained on facial emotion datasets.
- It consists of convolutional layers, max pooling, batch normalization, and dropout layers.
- The trained model is stored in `bestmodel.h5`, and the architecture is in `model.json`.

## Usage
1. The script captures video from the webcam.
2. Faces are detected using OpenCV’s Haar cascade classifier.
3. The detected face is processed and fed into the trained model.
4. The model predicts the emotion and displays it on the screen.

## Face Emotion Categories
- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral



## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## Author
AdhilAbu9072

