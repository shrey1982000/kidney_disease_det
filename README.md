This project provides a computer vision solution for medical image analysis using deep learning, it is used for the classification of kidney diseases. 
The dataset used is a CT scan dataset named CT KIDNEY DATASET: Normal-Cyst-Tumor and Stone from kaggle, and it incorporates transfer learning using
the effnet model, as it allows the rusability of features for faster convergence especially for scarce datasets like the ones for medical field. It 
applies various set of augmentations necessary for medical images to make the model more robust to real settings and mimic patient behaviour and 
errors caused due to the medical equipment.

It achieved 94% Classification upon its detection
It also has the implementation for explanable ai using the GRAD-CAM 
visualization


Technologies Used


Deep Learning Framework

TensorFlow 
Keras 
EfficientNet 


Data Processing & Augmentation


Albumentations 
OpenCV 
NumPy 
Pandas 


Optimization & Visualization


Keras Tuner 
Matplotlib 
Seaborn 
Grad-CAM
