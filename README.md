# Sketch Match: Image Retrieval System  
![FEATURING MATCHING](https://github.com/user-attachments/assets/11f55d4d-1ef0-4ba0-8132-2f9838c5f1e8)
![FIXED IMG](https://github.com/user-attachments/assets/f11860fa-0124-4005-9b2d-4e66127cab92)

## Overview  
The **Sketch Match** system is a robust tool for sketch-based image retrieval and restoration. It operates in two primary stages:  

### 1. Image Matching  
- Utilizes **SIFT (Scale-Invariant Feature Transform)** and **FLANN (Fast Library for Approximate Nearest Neighbours)** for feature detection and matching key points between images.  
- Identifies the best match for a distorted or low-quality sketch from a predefined database of sketches.  

### 2. Image Restoration & Retrieval  
- Enhances distorted sketches using **CLAHE (Contrast Limited Adaptive Histogram Equalization)** and **LAB color space adjustments**.  
- Matches the restored sketch with a database of original images to retrieve the correct image.  

---

## Features  
- **Content-Based Image Retrieval (CBIR)** for sketch-based search.  
- Accurate feature detection and matching using SIFT and FLANN.  
- Robust image restoration techniques for distorted sketches.  
- Comprehensive evaluation metrics, including **SSIM (Structural Similarity Index)** and **MSE (Mean Squared Error)**.  

---

## Applications  
1. **Forensics**: Identifying suspects or objects from rough sketches.  
2. **Art Restoration**: Recovering and matching historical sketches with their original works.  
3. **Creative Design**: Bridging sketches with digital imagery for inspiration or prototyping.  

---

## Technical Highlights  

### Dataset  
- The **CUHK Face Sketch Database (CUFS)**, comprising 188 images and their corresponding sketches, served as the foundation for training and testing.  

### Methodology  
1. Distorted sketches were manually created and restored using CLAHE and LAB adjustments.  
2. Matches were refined with **RANSAC (Random Sample Consensus)** for accurate geometric transformations.  

### Performance Evaluation  
- **MSE** and **SSIM** metrics ensured restoration quality and visual fidelity.  

---

## Technologies Used  

### Programming Language  
- **Python**: Used for implementing the project.  

### Libraries and Frameworks  
1. **OpenCV**  
2. **NumPy**
3. **Matplotlib**
   
### Algorithms and Techniques  
1. **SIFT (Scale-Invariant Feature Transform)**:  
   - Feature detection and descriptor computation.  
2. **FLANN (Fast Library for Approximate Nearest Neighbours)**:  
   - Efficient feature matching between sketches and images.  
3. **CLAHE (Contrast Limited Adaptive Histogram Equalization)**:  
   - Enhancing image contrast in the luminance channel.  
4. **RANSAC (Random Sample Consensus)**:  
   - Robust homography estimation to refine matches.  
5. **LAB Color Space Transformation**:  
   - Separating luminance and chrominance components for effective restoration.  

### Tools and Platforms  
- **CUHK Face Sketch Database (CUFS)**:  
   Dataset for sketches and corresponding original images.  

### Metrics and Evaluation  
1. **SSIM (Structural Similarity Index)**:  
   - To evaluate perceptual similarity between restored and original images.  
2. **MSE (Mean Squared Error)**:  
   - For quantifying restoration accuracy.  

---

## How to Run 
1. Fork and download  
2. Extract the archive.zip in the same file with SketchMatch.ipynb file
3. change the paths if required in the code

---

## Results  
The system successfully demonstrates:  
- Accurate retrieval of original images based on distorted sketches.  
- Significant restoration of sketch quality with high visual fidelity.  

---

## Authors  
- **Chinmay Srivastava** – BML Munjal University, Gurugram, Haryana  
  - Email: [chinmayy10@gmail.com]  
- **Raghuvansh Singh Parmar** – BML Munjal University, Gurugram, Haryana  
  - Email: [raguvanshsingh.parmar.22cse@bmu.edu.in]  

---

## Conclusion  
The **Sketch Match** project provides an efficient and scalable solution for sketch-based image retrieval and restoration, making it a valuable tool for real-world applications requiring high precision and adaptability.  

---  
