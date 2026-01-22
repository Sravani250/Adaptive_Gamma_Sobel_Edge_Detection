# Adaptive_Gamma_Sobel_Edge_Detection
# Adaptive Gamma-Weighted Guided Sobel Edge Detection

## Overview
This project implements an extended edge detection technique in the Digital Image Processing (DIP) domain titled **Adaptive Gamma-Weighted Guided Sobel Edge Detection**.  
The proposed method enhances traditional Sobel edge detection by combining adaptive gamma correction with guided filtering to improve edge clarity, continuity, and noise suppression under varying illumination conditions.

The complete implementation and experimentation are performed using Python in Google Colab.

---

## Objectives
- Enhance edge detection performance in low-contrast and unevenly illuminated images  
- Suppress noise while preserving fine structural details  
- Improve edge continuity compared to classical Sobel and Canny methods  
- Quantitatively evaluate performance using standard image quality metrics  

---

## Proposed Method (Extended)
The extended method consists of the following key components:

1. **Adaptive Gamma Weighting**
   - Dynamically adjusts gamma values based on local image intensity distribution  
   - Enhances contrast selectively in dark and bright regions  

2. **Guided Filtering**
   - Performs edge-preserving smoothing  
   - Reduces noise without blurring important edges  

3. **Guided Sobel Edge Detection**
   - Applies Sobel operators on the refined image  
   - Produces sharper and more continuous edge maps  

---

## Methodology / Pipeline
1. Input image acquisition  
2. Grayscale conversion and normalization  
3. Adaptive gamma correction  
4. Guided filtering for noise suppression  
5. Sobel gradient computation  
6. Edge magnitude enhancement  
7. Performance evaluation using metrics  

---

## Performance Evaluation
The proposed method is evaluated using the following metrics:
- **PSNR (Peak Signal-to-Noise Ratio)**
- **SSIM (Structural Similarity Index)**

### Results
- Achieved approximately **30–40% improvement** in edge sharpness and boundary continuity  
- Demonstrated superior visual quality compared to traditional Sobel and Canny edge detection methods  

---

## Technologies Used
- **Programming Language:** Python  
- **Libraries:** OpenCV, NumPy, SciPy, Matplotlib, scikit-image  
- **Platform:** Google Colab  

---

## Run in Google Colab
Click the link below to run the complete implementation:

**Open in Colab:**  
https://colab.research.google.com/drive/10hSZoHCOk7dlwSvzZ2_yne2-t0fPNXNO?usp=drive_link

---

## Repository Structure


---

## Future Work
- Evaluation on larger benchmark datasets (e.g., BSDS300)  
- Comparison with advanced and deep learning-based edge detectors  
- Optimization for real-time edge detection applications  

---

## Author
**Aala Sravani**  
Final-year B.Tech – Information Technology  
Guntur, Andhra Pradesh  

GitHub: https://github.com/Sravani250
LinkedIn: https://www.linkedin.com/in/aala-sravani-3b2a8a308  

