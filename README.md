# TMREF-AD: Trust-Aware Multimodal Regional Expert Fusion for Alzheimer's Disease Diagnosis

> **Bachelor's Thesis Defense Presentation**
> Department of Computer Science and Engineering
> Bangladesh University of Engineering and Technology (BUET)

This repository contains the presentation slides for my undergraduate thesis:

**TMREF-AD: Trust-Aware Multimodal Regional Expert Fusion for Alzheimer's Disease Diagnosis**

---

## 📖 Overview

Alzheimer's disease (AD) is a progressive neurodegenerative disorder whose early diagnosis remains challenging due to heterogeneous disease progression and the complementary nature of different neuroimaging modalities.

TMREF-AD proposes a **Trust-Aware Multimodal Regional Expert Fusion** framework that integrates structural MRI and PET imaging for accurate, reliable, and interpretable Alzheimer's disease classification. The framework explicitly models clinically meaningful brain regions and adaptively aggregates regional predictions using a trust-aware expert fusion mechanism.

---

## 📂 Repository Contents

```
.
├── TMREF-AD_Thesis_Slides.pdf
├── figures/
├── assets/
└── README.md
```

---

## 🎯 Presentation Outline

The presentation includes:

* Problem Definition and Motivation
* Related Work
* Proposed TMREF-AD Framework
* MRI & PET Data Preprocessing
* Regional Brain Partitioning
* Intra-modal Attention
* Regional Expert Fusion
* Trust-Aware Routing Mechanism
* Experimental Evaluation
* Ablation Studies
* Explainability Analysis
* Research Contributions
* Limitations and Future Work
* Conclusion

---

## 🧠 Proposed Framework

The TMREF-AD framework consists of six major stages:

1. MRI and PET preprocessing
2. Brain segmentation using FastSurfer
3. Regional MRI & PET feature extraction
4. Intra-modal attention learning
5. Trust-aware regional expert fusion
6. Final Alzheimer's disease classification

The framework divides the brain into **five clinically meaningful anatomical regions** and estimates a trust score for each regional expert before combining their predictions.

---

## ✨ Key Contributions

* Region-aware multimodal MRI–PET representation learning
* Anatomically meaningful brain partitioning
* Intra-modal attention for inter-regional dependency modeling
* Mixture-of-experts inspired regional fusion
* Trust-aware expert aggregation using:

  * Patient-specific routing
  * Prediction confidence
  * Historical expert reliability
* Interpretable regional importance estimation
* State-of-the-art performance for CN/MCI/AD classification on the ADNI dataset

---

## 📊 Experimental Results

| Metric         |      Score |
| -------------- | ---------: |
| Accuracy       | **93.70%** |
| Recall         | **91.51%** |
| Precision      | **92.19%** |
| Specificity    | **94.88%** |
| Macro F1-score | **91.85%** |

TMREF-AD outperforms several representative multimodal Alzheimer's disease diagnosis methods while providing interpretable regional trust scores that highlight the anatomical regions contributing most strongly to each prediction.

---

## 🛠️ Technologies Used

* Python
* PyTorch
* MONAI
* FastSurfer
* CUDA
* MRI
* PET
* Deep Learning
* Computer Vision

---

## 🔬 Research Areas

* Medical Image Analysis
* Deep Learning
* Computer Vision
* Multimodal Learning
* Explainable AI (XAI)
* Trustworthy AI
* Biomedical Artificial Intelligence
* Alzheimer's Disease Diagnosis

---

## 👨‍🎓 Thesis Information

**Title**

TMREF-AD: Trust-Aware Multimodal Regional Expert Fusion for Alzheimer's Disease Diagnosis

**Author**

Adnan Ibney Faruq

**Supervisor**

Dr. Mohammad Mahfuzul Islam

Department of Computer Science and Engineering

Bangladesh University of Engineering and Technology (BUET)

---

## 📚 Citation

If you find this work useful, please consider citing:

```bibtex
@thesis{faruq2026tmrefad,
  title     = {TMREF-AD: Trust-Aware Multimodal Regional Expert Fusion for Alzheimer's Disease Diagnosis},
  author    = {Adnan Ibney Faruq},
  school    = {Bangladesh University of Engineering and Technology},
  year      = {2026},
  type      = {Bachelor's Thesis}
}
```

---

## 📄 License

This repository is intended for academic and research purposes.

© 2026 Adnan Ibney Faruq. All rights reserved.
