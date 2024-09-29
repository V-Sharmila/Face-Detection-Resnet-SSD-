**Face Detection Using ResNet SSD**
This project demonstrates face detection using a pre-trained ResNet-10 SSD (Single Shot Multibox Detector) model in OpenCV. The model is capable of detecting faces in real-time using a webcam.

**Model Overview**
Model Architecture: ResNet-10
Detection Method: Single Shot Multibox Detector (SSD)
Dataset: Pre-trained on the WIDER Face dataset.
Framework: OpenCV's Deep Neural Network (DNN) module.

**How It Works**
The face detection model processes each frame from the webcam feed in real-time. It converts the frame to a 300x300 image, normalizes it, and passes it through the ResNet-10 SSD model. The model outputs detected faces with confidence scores, which are then displayed with bounding boxes on the screen.

**Requirements**
To run this project, you'll need the following dependencies:
  Python 3.x
  OpenCV
  
**Model Files**
You need to download the model files given.

**Code Structure**
face_detection.py: The main script that captures webcam video, detects faces, and displays them with bounding boxes.
deploy.prototxt: Defines the model architecture.
res10_300x300_ssd_iter_140000.caffemodel: Pre-trained model weights for face detection.

