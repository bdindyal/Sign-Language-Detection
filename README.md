# Sign-Language-Detection

**Overview**:  <br />
This project is a real-time sign language detection system developed using Python. The system uses Action Recognition techniques like Long Short-Term Memory (LSTM) to predict hand gestures representing various sign actions, with a high degree of accuracy. The model was trained using a curated dataset of 1662 landmark values, achieving a prediction accuracy of 95%. The neural network architecture also includes dynamic visualizations, which display the probabilities for different sign actions in real-time.

**Features:**  <br />
Real-time Sign Language Detection: Detects and classifies hand gestures in real-time using sequences of frames.  <br />
LSTM-based Neural Network: Leverages Action Recognition techniques to model the temporal dependencies between consecutive frames.  <br />
Curated Dataset: The system is trained on a dataset of 1662 key landmark values extracted from sign language gestures.  <br />
High Accuracy: Achieves 95% accuracy in predicting sign actions.  <br />
Dynamic Visualization: Visualizes real-time predictions by displaying probability distributions for various actions.  <br />

**Tech Stack:**  <br />
Programming Language: Python  <br />
TensorFlow/Keras: For building and training the neural network.  <br />
MediaPipe: For extracting landmark values from hand gestures.  <br />
OpenCV: For handling real-time video input from the webcam.  <br />
Matplotlib: For visualizing the action probabilities in real-time.  <br />

**Getting Started:**  <br />
Prerequisites:  <br />
Before running the project, ensure you have the following installed:  <br />
Python 3.8+  <br />
TensorFlow  <br />
MediaPipe  <br />
OpenCV  <br />
Matplotlib  <br />

**Dataset:**  <br />
The dataset consists of 1662 landmark values per sign action, which are extracted using MediaPipe. These landmark values represent key points on the hand, allowing the system to differentiate between different gestures.

**Model Architecture:**  <br />
The core of the system is an LSTM-based neural network that processes sequences of landmark frames. By analyzing the temporal relationships between these frames, the model can accurately predict sign actions.

**The network architecture includes:**  <br />
LSTM layers are used to model the time-dependent behaviour of hand gestures.  <br />
Dense layers are used to classify the gestures into distinct sign actions.  <br />
Softmax activation to output probabilities for each possible sign action.  <br />

**Results:**  <br />
The system achieves 95% accuracy in predicting hand gestures, with real-time performance for video input. The dynamic visualization displays the probability distribution of detected gestures as the video feed updates.
