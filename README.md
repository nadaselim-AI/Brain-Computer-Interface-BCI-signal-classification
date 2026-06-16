# Brain-Computer-Interface-BCI-signal-classification
A Brain-Computer Interface (BCI) machine learning project for EEG-based motor imagery classification using CSP feature extraction and SVM/Gaussian Naive Bayes classifiers.
## Problem
Classifying EEG brain signals to detect imagined hand movements (left vs right) — enabling hands-free control systems for paralyzed patients or human-machine interfaces.
 
## Approach
- Loaded and preprocessed raw EEG data from the BCI Competition IV Dataset 1
- Applied bandpass filtering (8–30 Hz) to isolate motor imagery frequency bands
- Used Common Spatial Pattern (CSP) for feature extraction
- Trained and evaluated multiple classifiers (Gaussian Naive Bayes, SVM)
- Evaluated across 5 participants for generalizability
## Results
| Metric | Score |
|--------|-------|
| Average Accuracy | 83% |
| Evaluation | 5-fold cross-participant |
 
## Stack
- Python
- MNE (EEG processing)
- Scikit-learn
- NumPy
- SciPy
- Matplotlib
## Dataset
BCI Competition IV — Dataset 1  
EEG recordings from multiple participants performing motor imagery tasks.
 
## How to Run
```bash
# Install dependencies
pip install mne numpy scipy scikit-learn matplotlib
 
# Open the notebook
Google Colab BCI_PROJECT_LOAD_DATA.ipynb
```
 
## Key Concepts Used
- EEG signal preprocessing and filtering
- Common Spatial Pattern (CSP) feature extraction
- Motor imagery classification
- Cross-participant evaluation
## Author
Nada Selim — Computer Vision & ML Engineer  
[LinkedIn](https://www.linkedin.com/in/nada-selim-phd-student-a053b5223) | [GitHub](https://github.com/nadaselim-AI)
