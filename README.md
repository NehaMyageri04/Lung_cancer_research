# Lung_cancer_research
Near-Perfect Lung Cancer Classification Using Deep Learning

#Abstract—Accurate lung cancer diagnosis continues to be an issue, and it becomes more so as fewer changes can be spotted within tiny samples at an early stage of lung cancer. This article proposes a learning model that aims to classify images of lung histopathology as benign samples, adenocarcinoma, and squamous cell carcinoma. The solution uses the MobileNetV2 technique for feature extraction and classification, and it has been strengthened via some preprocessing steps and data augmentation techniques. Because clinical choices depend greatly on evidence, the system uses Grad-CAM (Gradient-weighted Class Activation Mapping) to generate justifications that identify the specific areas of the tissue slide impacting the prediction, enhancing the transparency and interpretability of the result. The general effectiveness is assessed through accuracy, confusion matrices, and confidence visualization. This method seeks to provide an interpretable and effective aid for pathologists in their diagnostic evaluations.
Keywords—Lung Cancer Detection, Histopathology Images, Deep Learning, MobileNetV2, Explainable AI, Grad-CAM, Cancer Classification.

#methodology 
Model Usage Summary

The trained deep learning model is loaded using TensorFlow/Keras and is designed to classify lung histopathology images into three categories: Adenocarcinoma, Normal/Benign, and Squamous Cell Carcinoma. Input images are resized to 224 × 224, normalized, and passed through the model to obtain class probabilities. The predicted class corresponds to the highest probability, along with a confidence score.

The system supports both single-image inference and batch prediction, enabling efficient analysis of multiple images in one run. Prediction results include the image name, predicted class, and associated confidence value.

System and Software Requirements

The implementation requires Python 3.8 or higher with TensorFlow 2.x/Keras. Model training benefits from an NVIDIA T4 GPU or better with at least 16 GB VRAM, while a minimum of 12 GB system RAM is recommended. Approximately 2 GB of storage is required for the dataset and trained models.

Key dependencies include TensorFlow, NumPy, Scikit-learn, Matplotlib, Seaborn, and OpenCV. The trained model files (lung_robust_final.keras and lung_final.keras) are lightweight, each approximately 10 MB, enabling easy deployment.

#results 
<img width="514" height="179" alt="image" src="https://github.com/user-attachments/assets/3cbabb9b-b705-40df-890f-92b12af29bd1" />
<img width="448" height="172" alt="image" src="https://github.com/user-attachments/assets/085c6adb-3829-4586-ad87-b6bf58740906" />
<img width="352" height="261" alt="image" src="https://github.com/user-attachments/assets/1525ffc9-ad59-456a-af92-d112652b4b72" />
<img width="431" height="145" alt="image" src="https://github.com/user-attachments/assets/104fbd33-6a21-4465-8fef-6e779b8bfb38" />

https://github.com/Kushal-Raj-135/Lung-cancer



