# An Advanced Deep Learning-Based System for Face Recognition

A deep learning-based attendance system that uses facial recognition to identify students. Built with TensorFlow and MobileNetV2, this project automates the attendance process by recognizing student faces from images. It compares different deep learning approaches, including custom CNN and transfer learning, to determine the most effective model for this task. 

---

## Project Objectives

- Design and develop a deep learning-based face recognition system for student identification and automated attendance marking.
- Collect and build a custom face dataset consisting of facial images from 10 individual students under various lighting conditions, angles, and expressions to simulate real-world scenarios.
- Perform data preprocessing and augmentation, including:
  - Face detection and alignment
  - Resizing and normalization
  - Rotation, flipping, brightness variation to enhance generalization and model robustness.
- Explore and compare multiple deep learning architectures for facial recognition:
  - A custom Convolutional Neural Network (CNN) built from scratch
  - MobileNetV2 with frozen pretrained layers (feature extractor)
  - MobileNetV2 with fine-tuned custom convolutional layers
- Train and evaluate the models using training/validation/testing splits, and analyze performance based on Accuracy
- Model size and inference time (if real-time deployment is intended)
- Optimize model performance through hyperparameter tuning (e.g., learning rate, batch size, dropout) and regularization techniques.
---

---

## Project Objectives

Manual attendance systems are time-consuming, error-prone, and susceptible to fraudulent practices such as proxy attendance. Traditional biometric methods like fingerprint or ID card scanning require physical contact or hardware, which is inconvenient and inefficient, especially in post-pandemic environments where contactless systems are preferred. There is a growing need for a smart, automated, and contactless attendance system that can reliably identify individuals in real-time using facial recognition, even with limited training data and constrained computational resources.

---

---

## Aim

To develop an advanced deep learning–based face recognition system that can accurately identify students and automate the attendance process using real-time facial recognition. The system aims to compare custom CNN and MobileNetV2-based transfer learning models, optimize model performance, and prepare the system for future deployment using live camera feeds or mobile devices.

---


## Tools & Technologies

- **Language:** Python  
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Pandas  
- **Framework:** Jupyter Notebook  
- **Model Architectures:** CNN, MobileNetV2 (Transfer Learning)  
- **Dataset:** 100 manually cropped images of 10 students (10 images each)

---

## Folder Structure

- `report/`: Final project report (Word document)  
- `src/`: Source code for model training and architecture  
- `results/`: Training accuracy/loss graphs and performance plots  
- `requirements.txt`: List of Python packages needed  
- `.gitignore`: Files ignored by Git (e.g., `__pycache__`, temp files)  
- `LICENSE`: MIT license for open-source sharing  
- `README.md`: This documentation file

---

## 🚀 How to Run
### 1. Install the required librarie
  ``` bash
   pip install -r requirements.txt
```

### 2. Run the Models (Optional)

To train and evaluate the models, open and run the following Jupyter notebooks:

1. `custom_cnn_(model_1)_.py`
2. `mobilenetv2_(frozen_base_model_2).py`
3. `mobilenetv2_+_fine_tuned_(model_3).py`
  
**Instructions:**
- Open each python files using Jupyter Notebook or JupyterLab.
- Each notebook contains code to load data, train models, and display results.

### 3. Run the Real-Time Attendance System (Optional)

To test the real-time facial recognition attendance system using your webcam:
1. `attendance_system_.py`

**Instructions:**
- Ensure you have a webcam connected and the best-performing trained model saved.
- Open and run the script using any Python IDE or terminal
- The script will:
  - Detect faces from the webcam in real-time
  - Predict identities using the trained model
  - Display names and confidence scores on the screen
  - Automatically log attendance to a CSV file

Note: Press q to stop the webcam stream and save the attendance log.

## Results

| Model                                | Training Accuracy | Validation Accuracy |
|-------------------------------------|-------------------|---------------------|
| Custom CNN (Model 1)                | 100%              | 15%                 |
| MobileNetV2 (Frozen Base - Model 2) | 63%               | 65%                 |
| MobileNetV2 + Fine-Tuned (Model 3)  | 76%               | 75%                 |

**Best performing model:** MobileNetV2 + Fine-Tuned Custom Layers  
The model achieved excellent generalization despite limited training data.

---

## Limitations

- Dataset includes only 10 students (100 images total, Small Dataset).

---

## Future Improvements

- Liveness detection to prevent spoofing (e.g., printed photos)
- Mobile or Raspberry Pi deployment
- Integration with institutional attendance systems
- Expansion to support 100+ students and multiple classes

---

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for full details.

---

## Author Details

- **Name:** TM Kahavidhana   
- **University:** General Sir John Kotelawala Defence University  
- **Degree Program:** B.Sc. (Hons) in Data Science and Business Analytics  
- **Course:** CS 4132 - Image Processing & Computer Vision  
- **Submission Date:** 07.04.2025

