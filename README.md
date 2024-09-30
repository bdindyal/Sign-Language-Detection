# Sign-Language-Detection

**Overview**:
This project is a real-time sign language detection system developed using Python. The system uses Action Recognition techniques like Long Short-Term Memory (LSTM) to predict hand gestures representing various sign actions, with a high degree of accuracy. The model was trained using a curated dataset of 1662 landmark values, achieving a prediction accuracy of 95%. The neural network architecture also includes dynamic visualizations, which display the probabilities for different sign actions in real-time.

**Features:**
Real-time Sign Language Detection: Detects and classifies hand gestures in real-time using sequences of frames.
LSTM-based Neural Network: Leverages Action Recognition techniques to model the temporal dependencies between consecutive frames.
Curated Dataset: The system is trained on a dataset of 1662 key landmark values extracted from sign language gestures.
High Accuracy: Achieves 95% accuracy in predicting sign actions.
Dynamic Visualization: Visualizes real-time predictions by displaying probability distributions for various actions.

**Tech Stack:**
Programming Language: Python

**Libraries:**
TensorFlow/Keras: For building and training the neural network.
MediaPipe: For extracting landmark values from hand gestures.
OpenCV: For handling real-time video input from the webcam.
Matplotlib: For visualizing the action probabilities in real-time.

**Getting Started:**
Prerequisites:
Before running the project, ensure you have the following installed:
Python 3.8+
TensorFlow
MediaPipe
OpenCV
Matplotlib

**Dataset:**
The dataset consists of 1662 landmark values per sign action, which are extracted using MediaPipe. These landmark values represent key points on the hand, allowing the system to differentiate between different gestures.

**Model Architecture:**
The core of the system is an LSTM-based neural network that processes sequences of landmark frames. By analyzing the temporal relationships between these frames, the model can accurately predict sign actions.

**The network architecture includes:**
LSTM layers to model time-dependent behavior of hand gestures.
Dense layers for classification of the gestures into distinct sign actions.
Softmax activation to output probabilities for each possible sign action.

**Results:**
The system achieves 95% accuracy in predicting hand gestures, with real-time performance for video input. The dynamic visualization displays the probability distribution of detected gestures as the video feed updates.
