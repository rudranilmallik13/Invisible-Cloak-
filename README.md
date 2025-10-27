# Invisible Cloak using OpenCV

This project creates a **magical invisibility effect** using computer vision!  
By detecting a specific color (like a red or blue cloth), the program replaces those colored pixels with the **background**, making the object appear **invisible** 🪄.

---

## Project Overview

The **Invisible Object** project leverages **OpenCV** for real-time color detection and segmentation to simulate the illusion of invisibility.  
It’s inspired by the concept of a "cloaking device" — when a person holds a particular colored cloth, that color region is replaced by the background captured earlier.

---

## Working Principle

1. **Color Detection & Segmentation:**  
   OpenCV detects a particular color (for example, red) using color thresholding in the **HSV color space**.

2. **Background Capture:**  
   The program first records the background for a few seconds before the subject enters the frame.  
   This background is later used to replace pixels of the cloak.

3. **Cloak Replacement:**  
   When the cloak (of the selected color) is detected, its pixels are replaced with the corresponding background pixels — creating the **invisibility effect**.

---

## Tech Stack

- **Language:** Python  
- **Libraries:** OpenCV, NumPy  
- **Concepts Used:**  
  - Image Segmentation  
  - Color Masking in HSV  
  - Bitwise Operations  
  - Frame Blending  

---
