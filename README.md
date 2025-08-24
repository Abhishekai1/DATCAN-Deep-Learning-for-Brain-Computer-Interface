# DATCAN: Domain-Adversarial TRCA-Contrastive Network for Subject-Independent SSVEP BCI

⚡ Developed an advanced framework that pushes the boundaries of **Brain–Computer Interfaces (BCIs)** by combining **deep learning**, **signal processing**, and **domain adaptation**.

This work demonstrates my ability to design **novel architectures** that integrate **neuroscience priors** with **state-of-the-art ML techniques** — achieving competitive results in **plug-and-play, calibration-free BCIs**.

---

## 🔥 My Contributions
- Designed **DATCAN**, a **new deep model** that fuses:
  - TRCA-inspired covariance consistency (trial stability).
  - Contrastive alignment between EEG and synthetic harmonic references.
  - Domain-invariant representation learning (adversarial + DeepCORAL).
  - Ensemble fusion with FBCCA for robust decoding.
- Built a **Kaggle-ready pipeline**:  
  - Runs on **CPU, GPU, and TPU** with reproducibility in mind.  
  - Handles multiple public EEG datasets seamlessly.  
  - Outputs **publication-quality plots, stats, and LOSO evaluations**.
- Conducted a **comprehensive experimental study**:  
  - Leave-One-Subject-Out (LOSO) evaluation.  
  - Accuracy/ITR trade-offs across window lengths (1–4s).  
  - Ablations with/without CORAL and hybrid ensembles.

---

## 📊 Key Achievements
- **Strong LOSO results** (no subject calibration):  
  - ~80% mean accuracy with 12 SSVEP targets.  
  - Up to **99% single-subject accuracy**.  
- **High-speed decoding**:  
  - **100–140 bits/min ITR** with 1-second trials.  
- **State-of-the-art relevance**:  
  - Results competitive with recent deep-learning SSVEP papers.  
  - Fully reproducible with open datasets.

---

## 🧠 Why It Matters
- Tackles one of the **hardest problems in BCI**: subject variability.  
- Reduces calibration time from **30 minutes to near zero**.  
- Provides a framework for **accessible communication tools** for people with ALS, paralysis, or speech impairments.  
- Contributes to **next-gen human–AI interaction** (AR/VR, neurorehab, assistive robotics).

---

## 🚀 Tech Stack
- **Languages/Frameworks**: Python, PyTorch, NumPy, SciPy, Matplotlib.  
- **Optimization**: AdamW, GRL (Gradient Reversal), DeepCORAL.  
- **Evaluation**: LOSO CV, confusion matrices, ITR calculations.  
- **Deployment**: Kaggle CPU/GPU/TPU environments.

---

## 📂 Repository Structure
```

├── datcan_train.py        # End-to-end training & evaluation
├── results/               # CSV summaries and figures
├── requirements
└── README.md              # This file

````

---

## 📈 Results Snapshot
- Confusion matrices saved for each subject.
- Bar plots with mean ± 95% CI.
- Accuracy vs. window length & ITR trade-off curves.

Example:

| Window Length | Mean Acc. | Best Subj. Acc. | Mean ITR (bits/min) |
|---------------|-----------|-----------------|----------------------|
| Full (~4.1s)  | ~82%      | 99%             | ~45–50              |
| 2.0s          | ~70%      | ~89%            | ~60–70              |
| 1.0s          | ~53%      | ~83%            | 100–140             |

---

## 🏆 Impact
This project showcases my ability to:
- Take a **challenging neurotechnology problem** and design a **deep learning solution**.  
- Integrate **classic signal processing** and **modern ML** into a cohesive pipeline.  
- Produce **publication-ready results and visualizations**.  

---

## 📖 Citation
```bibtex
@article{YourName2025DATCAN,
  title={DATCAN: Domain-Adversarial TRCA-Contrastive Network for Subject-Independent SSVEP BCI},
  author={Your Name},
  year={2025},
  journal={arXiv preprint}
}
````

---

````
