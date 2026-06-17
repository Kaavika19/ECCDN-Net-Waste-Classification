ECCDN-Net: Waste Classification using Deep Learning and YOLOv8

About the Project

This project was developed to explore how deep learning can be used for automated waste segregation. The system classifies waste into Organic and Recyclable categories using a hybrid model built from DenseNet121 and ResNet18. YOLOv8 was also integrated to detect waste objects and draw bounding boxes around them.

Dataset

* RealWaste Dataset
* ~6,046 images after preprocessing and augmentation

Features

* Waste classification using transfer learning
* Hybrid DenseNet121 + ResNet18 architecture
* Data augmentation and class balancing
* YOLOv8-based object detection
* Performance evaluation using Confusion Matrix and ROC Curve

Technologies Used

Python, PyTorch, OpenCV, YOLOv8, NumPy, Matplotlib, Google Colab

Result

The hybrid model achieved better performance than the individual ResNet and DenseNet models for binary waste classification.

Future Improvements

* Multi-class waste classification
* Real-time webcam support
* Mobile application deployment
