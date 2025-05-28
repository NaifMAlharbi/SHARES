# SHARES: Silent Help – Arabic Lip Reading Emergency System

**Authors**:  
- [Naif Alharbi](https://github.com/NaifMAlharbi)  
- [Sultan Alaqili](https://github.com/SL6I)  
- [Yasser Alharbii](https://github.com/yasser-alharbi)  
- [Nawaf Alandijany]()  
- [Abdulaziz Abutaleb](https://github.com/Abdulaziz0470)

---

## Overview

**SHARES** is an AI-powered system designed to recognize **Arabic emergency words from silent lip movements**. It addresses communication barriers in critical situations where speech is not possible — such as for individuals who are mute, in distress, or in noisy environments.

Built using an **R(2+1)D convolutional neural network**, the model was fine-tuned on a custom Arabic dataset to classify emergency-related terms like _"اسعاف"_ (ambulance) and _"النجدة"_ (help). The system processes webcam video input in real time and provides instant feedback by recognizing and displaying the detected word on screen.

---

## Key Features

- **Real-Time Predictions**  
  SHARES processes live video streams from a webcam and outputs predictions instantly.

- **Custom Arabic Dataset**  
  Trained on a curated set of 10 Arabic emergency-related words with visual-only input.

- **High Accuracy**  
  Achieved **76%** test accuracy on unseen samples.

- **Visual Feedback**  
  Displays bounding box around the mouth and overlays the recognized word on video feed.

---

## Use Cases

- Emergency communication in noisy or dangerous environments  
- Silent signaling for individuals with speech impairments  
- Assistive technology in medical and rescue scenarios

---

## Technologies Used

- Python  
- PyTorch  
- OpenCV  
- R(2+1)D CNN architecture  
- Custom video preprocessing pipeline  

---

> SHARES represents a step forward in combining **Computer Vision**, **Arabic NLP**, and **Assistive AI** to solve real-world problems where voice cannot be used.
