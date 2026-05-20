# Smart Attendance System via YOLOv9 Sunglasses

> Wearable face recognition attendance system — sunglasses with an embedded micro HD camera, powered by YOLOv9, running fully on-device.

---

## Authors

**Kaushal Sahu** & **Dr. Raman Raju** *(Instructor)*  
Dept. of Data Analytics and Mathematical Sciences, JAIN (Deemed-to-be University), Bengaluru, India  
📧 [kaushalsahuofficial@gmail.com](mailto:kaushalsahuofficial@gmail.com)<br>
📊 [Linkedin](https://www.linkedin.com/in/kaushal-sahu/)

---

## Overview

Standard attendance systems rely on fixed cameras or manual sign-ins. This research embeds a **YOLOv9 face recognition pipeline** into a pair of sunglasses running on a **Raspberry Pi 3B+** — detecting faces, matching identities, and logging attendance to a local CSV file in real-time. No internet. No manual input.

---

## Pipeline
> Camera → YOLOv9 Detection → HOG Features (Feature extraction) → SSIM Matching → CSV Log


**Hardware:** Micro HD camera · Raspberry Pi 3B+ · LiPo battery · activation switch.  
**Recognition:** Fine-tuned YOLOv9-S · HOG feature extraction · SSIM face matching.

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![YOLOv9](https://img.shields.io/badge/YOLOv9-FF6F00?style=flat&logo=pytorch&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=flat&logo=raspberrypi&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

---

## Privacy

All processing and storage is **fully local** — no biometric data leaves the device. Designed for opt-in, consent-based environments.

---

*Academic research — JAIN (Deemed-to-be University), Bengaluru · 2024*
