This project aims to detect whether a rider is wearing a helmet or not using the YOLOv8 object detection model. Helmet detection is a critical application for enhancing road safety by ensuring compliance with safety regulations.

Dataset
The dataset used for this project includes images of riders, categorized as either wearing a helmet or not.
Ensure that your dataset is properly labeled and split into training, validation, and test sets.
Model Architecture
YOLOv8: A state-of-the-art object detection model known for its speed and accuracy.
The model was fine-tuned to detect two classes: With Helmet and Without Helmet.
Training
Training Parameters:
Epochs: [Number of epochs used]
Batch Size: [Batch size]
Learning Rate: [Learning rate]
The model was trained on [mention the hardware if applicable] and took approximately [mention time] to complete training.
Inference
The trained model can be used to detect helmets in images or videos. Simply provide the path to the input image/video, and the model will output the detected regions.
Dependencies
Python 3.x
YOLOv8: [Link to YOLOv8 repository]
OpenCV: For image processing
NumPy: For numerical operations
Matplotlib: For visualizing results
