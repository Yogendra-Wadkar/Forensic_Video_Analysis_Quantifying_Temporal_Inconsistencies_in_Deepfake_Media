# Forensic Video Analysis: Quantifying Temporal Inconsistencies in Deepfake Media

## 📌 Overview

Digital misinformation has evolved beyond the reach of the naked eye. As synthetic media becomes increasingly sophisticated, distinguishing between authentic and AI-generated content—popularly known as **Deepfakes**—has become a critical challenge for platforms like Facebook, Google, and Twitter. Major tech entities are now investing millions to secure digital integrity, as these manipulated videos can undermine trust in journalism, politics, and social evidence.

This project moves beyond simple "black-box" detection. Instead, it employs **Forensic Video Analysis** to mathematically quantify the subtle "flicker" and pixel-level artifacts that emerge when AI models fail to maintain perfect temporal coherence across video frames.

---

## 🔬 Scientific Approach

Unlike standard classifiers that offer a binary yes/no answer, this repository focuses on **Explainable Forensics**. By decomposing video streams into individual frames and analyzing them using full-reference metrics, we can pinpoint exactly where a deepfake algorithm struggled to replicate a target's likeness.

### Core Methodologies:

* **Video Decomposition:** Systematically extracting high-resolution frames to analyze the evolution of forgeries over time.
* **Facial Landmark Analysis:** Utilizing precise detection and cropping to isolate the manipulated region of interest (the face) from the static background.
* **Error Quantization (MSE):** Calculating the **Mean Squared Error** to detect "spikes" in pixel-level noise, often indicating a frame-to-frame "flicker" or misalignment.
* **Structural Similarity (SSIM):** Measuring the preservation of luminance, contrast, and structure to identify textures that feel "AI-generated" compared to natural camera sensor noise.

---

## 📊 Key Insights

The value of this analysis lies in its **temporal visualization**. By plotting error metrics across the video's duration, we can identify specific timestamps where the deepfake generation model "lost" its tracking—a hallmark of synthetic manipulation that is often invisible during real-time playback.

> **Note:** This repository serves as a foundational study in digital forensics, providing the mathematical framework necessary to build more robust, blind deepfake detection systems in the future.

---

<img width="1121" height="593" alt="Image" src="https://github.com/user-attachments/assets/04e8d341-41c5-4920-b429-760178ba9dd5" />

---

### 🚀 Getting Started

Refer to the `Description` folder for a detailed technical breakdown of the mathematical proofs and the `Requirements` file to set up your local environment for forensic analysis.

---
 
