# SHARES: Silent Help - Arabic Lip Reading Emergency System

**Authors**:  
- Naif Alharbi  
- Sultan Alaqili  
- Yasser Alharbii  
- Nawaf Alandijany  
- Abdulaziz Abutaleb  
(Department of Computer Science and Artificial Intelligence, Umm Al Qura University, Saudi Arabia)

---

## 1. Project Overview

**SHARES (Silent Help: Arabic Lip Reading Emergency System)** is a deep learning–based framework designed to recognize **Arabic emergency words** by analyzing lip movements. It leverages an **R(2+1)D** convolutional neural network fine-tuned on a proprietary Arabic dataset to classify commonly used Arabic words in emergency scenarios (e.g., اسعاف, النجدة, etc.).

Key highlights of SHARES:
- **Real-Time Predictions**: Processes webcam input in real time and outputs recognized words.  
- **High-Level Accuracy**: Achieved **76%** test accuracy on a curated dataset of 10 Arabic words.  
- **User-Friendly**: Highlights bounding box around the speaker’s mouth and displays recognized words directly on the video feed.

---
## 2. Setup and Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/NaifMAlharbi/SHARES.git
   cd SHARES
     ```
2. Install Dependencies
   ```bash
   pip install -r requirements.txt
   ```
   
