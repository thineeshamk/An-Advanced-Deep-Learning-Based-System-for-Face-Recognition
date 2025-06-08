# Weather-Driven Solar Energy Forecasting

A deep learning-based attendance system that uses facial recognition to identify students. Built with TensorFlow and MobileNetV2, this project automates the attendance process by recognizing student faces from images. It compares different deep learning approaches, including custom CNN and transfer learning, to determine the most effective model for this task.

---

## Project Objectives

- Develop a facial recognition model to identify students and mark attendance.
- Explore three deep learning approaches:
  - Custom CNN from scratch
  - MobileNetV2 with frozen layers
  - MobileNetV2 with fine-tuned custom convolutional layers
- Use data augmentation and preprocessing to improve model performance.
- Evaluate results using accuracy and loss metrics.
- Prepare the system for future real-time deployment using cameras or mobile devices.

---

## Tools & Technologies

- **Language:** Python  
- **Libraries:** TensorFlow/Keras, OpenCV, NumPy, Matplotlib, Pandas  
- **Framework:** Google Colab  
- **Model Architectures:** CNN, MobileNetV2 (Transfer Learning)  
- **Dataset:** 100 manually cropped images of 10 students (10 images each)

---

## Machine Learning Models Used

| Model              | Type           | Purpose                             |
|-------------------|----------------|-------------------------------------|
| Lasso Regression  | Linear         | Baseline model, simple & interpretable |
| Random Forest      | Ensemble Trees | Good for handling non-linear data   |
| XGBoost            | Boosted Trees  | High performance with tuning        |
| LSTM               | Deep Learning  | Excellent for time-series forecasting|

---

## Technologies Used

- **Python**
- **Pandas, NumPy, Scikit-learn**
- **TensorFlow, Keras**
- **XGBoost**
- **Matplotlib, Seaborn**
- **Google Colab & VS Code**
- **Power BI & R Studio** (for visualization and statistics)
- **Streamlit** (for model deployment)

---

## Folder Structure

- `report/`: Final project report (Word document)  
- `src/`: Source code for model training and architecture  
- `saved_models/`: Trained `.h5` model files  
- `results/`: Training accuracy/loss graphs and performance plots  
- `requirements.txt`: List of Python packages needed  
- `.gitignore`: Files ignored by Git (e.g., `__pycache__`, temp files)  
- `LICENSE`: MIT license for open-source sharing  
- `README.md`: This documentation file

---


## 🚀 How to Run

1. **Install the required libraries**:

   ```bash
   pip install -r requirements.txt



## 📊 Results

| Model                                | Training Accuracy | Validation Accuracy |
|-------------------------------------|-------------------|---------------------|
| Custom CNN (Model 1)                | 100%              | 15%                 |
| MobileNetV2 (Frozen Base - Model 2) | 63%               | 65%                 |
| MobileNetV2 + Fine-Tuned (Model 3)  | 76%               | 75%                 |

✅ **Best performing model:** MobileNetV2 + Fine-Tuned Custom Layers  
🧠 The model achieved excellent generalization despite limited training data.

---

## 📌 Limitations

- Dataset includes only 10 students (100 images total).
- The system currently works only on uploaded images (not real-time).
- No database or attendance log integration yet.

---

## 🔮 Future Improvements

- Real-time webcam integration
- Liveness detection to prevent spoofing (e.g., printed photos)
- Mobile or Raspberry Pi deployment
- Integration with institutional attendance systems
- Expansion to support 100+ students and multiple classes

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for full details.

---

## 👨‍🎓 Author

- **Name:** TM Kahavidhana  
- **Index Number:** D/DBA/22/0017  
- **University:** General Sir John Kotelawala Defence University  
- **Degree Program:** B.Sc. (Hons) in Data Science and Business Analytics  
- **Course:** CS 4132 - Image Processing & Computer Vision  
- **Submission Date:** 07.04.2025

