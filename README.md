# 📡 Sensor Data Analysis — Amplitude Insights Over Time

Welcome to this analytical walkthrough of sensor-based amplitude data.  
This project explores **temporal patterns**, identifies **signal anomalies**, and applies **machine learning techniques** to classify sensor behavior.

---

## 🧰 Tools & Technologies

- **Python**: `pandas`, `numpy`, `matplotlib`, `scikit-learn`
- **Jupyter Notebook**: step-by-step exploration
- **Git**: version control and collaboration

---

## 📈 Workflow Overview

1. **Preprocessing**
    - Cleaned and structured sensor readings indexed by time  
    - Handled missing values and ensured time continuity  

2. **Visualization**
    - Line plots for selected sensor indexes  
    - Clear axis labels, legends, and titles for interpretability  

3. **Upsampling**
    - Increased sampling rate to 100 Hz using interpolation  
    - Preserved signal shape and time fidelity  

4. **Feature Selection**
    - Calculated average amplitudes  
    - Selected sensors with significant signal strength  

5. **Labeling**
    - Tagged sensors as anomaly or noise based on amplitude thresholds  
    - Transposed data for model compatibility  

6. **Modeling**
    - Applied classification models (*Logistic Regression*)  
    - Evaluated performance using confusion matrix, ROC curve, and accuracy metrics  

---

## 📊 Key Observations

- Upsampling revealed hidden signal fluctuations
- Feature selection improved model clarity
- Classification achieved reliable separation of signal types

---

## 🧠 Notes

- Code is **modular and reproducible**
- Visualizations are designed for clarity and presentation
- The notebook includes markdown summaries for each step

---

## 🤝 Contributions & Feedback

Feel free to **fork**, **explore**, or **suggest improvements**.  
This project is open to refinement and extension—whether through deep learning models, denoising filters, or alternative feature engineering.


