# SHARES Dataset

This document provides an overview of the dataset used for **SHARES (Silent Help: Arabic Lip Reading Emergency System)**, including its structure, content, and any preprocessing steps applied.

---

## 1. Overview

Our dataset focuses on **Arabic emergency words**. Specifically, we have **10 Arabic words** (e.g., "اسعاف" for Ambulance, "مساعدة" for Help), each spoken by **11 speakers**, with **3 repetitions** per speaker. This results in a total of **330 video clips** (`10 words × 11 speakers × 3 repetitions`).

1. Each video clip is approximately **1–2 seconds** long.
2. These clips contain **only** video frames (no audio), capturing lip movements.


---

## 2. Folder Structure

1. **`raw/`**  
   - Contains Original videos.

2. **`processed/`**  
   - Contains extracted and preprocessed frames for each video.
     

---

## 3. Data Collection

- **Number of Words**: 10 (e.g., اسعاف, النجدة, انتبه, اهرب, جريح, حريق, خطر, ساعدني, شرطة, مساعدة)  
- **Speakers**: 11  
- **Repetitions**: 3 per speaker  
- **Total Clips**: 330  
- **Clip Length**: 1–2 seconds each
- 

---

## 4. Preprocessing Steps

1. **Frame Extraction**  
   - Each video is sampled at **20 fps** (frames per second).  
   - A maximum of **20 frames** are extracted per clip. If a clip is shorter, we pad frames by repeating the last frame.

2. **Resizing**  
   - Each extracted frame is resized to **224×224 pixels**.

3. **Normalization**  
   - Pixel values scaled to the range `[0, 1]`.

4. **Data Augmentation (Training only)**  
   - Small random rotations (±2° or ±8°)  
   - Horizontal flips (p=0.2)  
   - Minor brightness/contrast jitter (±20%)  

---

## 5. Dataset Splits

We partition the 330 videos into:
- **Training**: 264 samples (80%)  
- **Development**: 33 samples (10%)  
- **Test**: 33 samples (10%)

---
## 6. Future Plans  
  - We aim to expand the dataset to include more words and more speakers from various dialect regions.  

For any queries about the dataset or requests for collaboration, please contact the maintainers listed in the main [README.md](../README.md).

