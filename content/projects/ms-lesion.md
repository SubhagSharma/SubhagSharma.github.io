---
title: "Multiple Sclerosis Lesion Segmentation"
summary: "Novel segmentation using SOTA U-Net architectures with deep feature extraction backbones."
tags: ["TensorFlow", "Keras", "Medical Imaging", "U-Net"]
weight: 1
# VISUAL HOOK: This appears on the list page and top of post
cover:
    image: "/images/brain-output.png"
    alt: "Segmentation Mask Output"
    caption: "Model prediction vs Ground Truth"
    relative: false
---

### 🎯 The Objective
Multiple Sclerosis (MS) is a rare neurological disease where early diagnosis is critical. The goal was to automate the segmentation of lesions in brain MRI scans to enhance diagnostic precision.

### 🛠️ Tech Stack
* **Core:** Python, TensorFlow, Keras
* **Imaging:** OpenCV, PyDicom, PIL
* **Models:** U-Net with ResNet/DenseNet backbones

### 🔬 Methodology
I performed a comprehensive evaluation of various U-Net combinations. By integrating deep feature extraction backbones (specifically ResNet and DenseNet), the model could capture finer contextual details in the MRI scans compared to standard architectures.

### 📊 Impact
The optimal configuration identified in this study demonstrated improved segmentation accuracy, potentially aiding clinicians in earlier diagnosis and treatment planning for MS patients.
### 📥 Downloads & Links

**[📄 Read Full Research Report (PDF)](/reports/ms-lesion-report.pdf)**

<!-- **[💻 View Source Code (GitHub)](https://github.com/SubhagSharma/your-repo)** -->