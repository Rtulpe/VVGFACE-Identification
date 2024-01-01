# Face Recognition System - Jupyter Notebook
This Jupyter Notebook implements a simple face recognition system using computer vision and deep learning techniques. The system captures video from a webcam, detects faces in real-time, and provides functionality for both reference face capture and face verification.

Prerequisites
Make sure you have the following libraries installed:

OpenCV (cv2)
MTCNN (mtcnn)
NumPy (numpy)
Keras VGGFace (keras_vggface)
SciPy (scipy)
Install the required dependencies using:

```
!pip install opencv-python mtcnn numpy keras_vggface scipy
```

## How to Use
Open the Jupyter Notebook (Notebook.ipynb).

Execute the cells in the notebook.

The notebook provides cells for the following actions:

Reference face capture: Run the corresponding cell to capture reference face(s) for recognition.

Face verification: Run the cell to verify faces against the reference face.

Follow the instructions in the notebook for further details and execution.

## Features
* Real-time face detection using the MTCNN algorithm.
* Reference face capture for recognition.
* Face verification against the reference face.
* Display of bounding boxes around detected faces with different   colors for reference and verified faces.

## Note
Ensure that your webcam is correctly connected and accessible. Execute the notebook cells as instructed. Feel free to modify and extend the notebook to meet specific requirements or integrate it into a larger project.