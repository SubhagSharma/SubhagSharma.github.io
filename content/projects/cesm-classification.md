---
title: "CESM Breast Cancer Classification"
summary: "Classifying probable malignant cases using subtracted images and Transfer Learning."
tags: ["Transfer Learning", "GradCam", "Saliency Maps", "Oncology"]
weight: 2
# VISUAL HOOK: This appears on the list page and top of post
# cover:
#     image: "/images/cesm-output.png"
#     alt: "GradCam Attention Map Output"
#     caption: "Workflow"
#     relative: false
#     hiddenInSingle: true
---

### 🎯 The Objective
To assist radio-oncologists in quickly identifying probable cancerous lumps in Contrast-Enhanced Spectral Mammography (CESM) images without immediate need for stat biopsies.
![CESM GradCam Analysis](static/images/cesm-cover.png)
*Figure 1: Workflow.*
### 🧠 Approach
* **Data Processing:** Utilized subtracted images to isolate potential masses.
* **Architecture:** Implemented Transfer Learning on shallow neural networks to maintain efficiency.
* **Explainability:** Integrated **Saliency Heatmapping** and **GradCam** to visualize *why* the model made a prediction—crucial for medical validation.

### 🏆 Results
Preliminary performance metrics indicate the model outperforms standard radiologist benchmarks in specific classification tasks. The results were validated in collaboration with a radio-oncologist.

**[📄 Read Full Research Report (PDF)](/reports/cesm-report.pdf)**

<!-- **[💻 View Source Code (GitHub)](https://github.com/SubhagSharma/your-repo)** -->