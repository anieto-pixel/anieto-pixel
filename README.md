# 👋 Hi, I'm Alicia Nieto  
Python Developer • Data Science Enthusiast • Scientific Computing

Welcome! I build intelligent tools that empower scientific analysis, from rock sample modeling to pulsar classification. My work often focuses on building human-centered applications that combine usability with rigor.

---

## Featured Projects

### ⚡ [ZarcFit-Demo](https://github.com/anieto-pixel/ZarcFit-Demo)  
*A user-friendly desktop app for fitting the impedance data from rock samples to theoretical models developed by the Canadian Geological Survey*

ZarcFit-Demo is a scientific GUI that helps researchers model rock sample impedance using curve-fitting techniques. It includes an interactive, DPI-aware interface with sliders, dynamic plots, and shortcut keys for streamlined exploration of complex experimental data.

- **Tech stack:** PyQt5, NumPy, custom signal processing modules  
- **Highlights:**
  - Time- and frequency-domain visualization
  - Cole and Bode model fitting
  - Supports various theoretical impedance models
  - Hotkey-mapped UI and live model updates
  - Flexible file input/output support
  - Tailored for geophysical and materials research workflows

> 🧩 Designed to make impedance modeling accessible to non-programmer researchers.

---

### 🌌 [Pick-Pulsar-Classifier](https://github.com/anieto-pixel/Pick-Pulsar-Classifier)  
*Sampler-classifier pipeline testing for astronomical pulsar classification*

This project evaluates how well different classifier and sampler combinations perform in identifying pulsars from a highly imbalanced dataset. It's tailored for **human-in-the-loop (HITL)** systems, where minimizing false negatives is more important than overall accuracy.

- **Tech stack:** Python, Jupyter, scikit-learn, imbalanced-learn, pandas  
- **Goal:** Favor recall for positive cases (pulsars) while managing class imbalance  
- **Features:**
  - Tests oversampling (SMOTE, ADASYN) and undersampling (TomekLinks, AllKNN) strategies
  - Automatically tunes classifiers (SVM, KNN, Decision Trees, etc.)
  - Cross-validation on both balanced and real-world (imbalanced) test sets
  - Visual summary of confusion matrices across strategies

> 📡 Built to help researchers assess and select models for pulsar candidate filtering in large-scale radio astronomy datasets.

---

## 🔧 Skills & Tools  
`Python` • `PyQt` • `NumPy` • `pandas` • `scikit-learn` • `matplotlib` • `imbalanced-learn`  
Scientific software design • Data analysis • GUI development • Signal processing

---

## 📫 Contact  
Want to collaborate or chat about your project? Feel free to reach out:  
- 📧 Email: aliciagnieto@gmail.com  

---

🛠️ *I write software that makes science easier to do and easier to trust.*
