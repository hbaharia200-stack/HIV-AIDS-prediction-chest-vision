# HIV-AIDS-prediction-chest-vision
A deep learning computer vision pipeline designed for the predictive classification of HIV/AIDS-associated pulmonary biomarkers and opportunistic infections using chest radiography
# HIV/AIDS Diagnostic Screening & Pulmonary Biomarker Prediction via Chest Radiography

An advanced medical computer vision infrastructure engineered to leverage deep convolutional neural networks (CNNs) for predicting HIV/AIDS-associated pulmonary indicators and opportunistic infections (such as Tuberculosis and Pneumocystis Pneumonia) directly from Chest X-ray (CXR) imagery.

## 🧠 Diagnostic Risk & Prediction Matrix

The intelligence engine processes chest images through two high-impact diagnostic layers:

### 1. High-Risk / Acute Clinical Biomarkers
*   **Trigger Mechanism:** Activated when the computer vision architecture detects spatial-temporal patterns, cavitary lesions, or diffuse opacities strongly correlated with severe immuno-compromised pulmonary states (CD4 count degradation indicators).
*   **System Action:** Flags the case as **High-Risk (Urgent Clinical Review Required)**, generating automated diagnostic payloads (`JSON`) to fast-track patient triaging within Hospital Information Systems (HIS).
*   **Optimization Focus:** Engineered with maximum *Sensitivity/Recall* to minimize critical false negatives in clinical environments.

### 2. Low-Risk / Normal Pulmonary Baseline
*   **Trigger Mechanism:** Validates clear lung fields and normal anatomical structures that present no statistically significant biomarkers of HIV-associated opportunistic infections.
*   **System Action:** Logs the screening as low-risk/routine, streamlining the clinical workflow and reducing diagnostic overhead for radiologists.

---

## 🛠️ Technical Stack & Framework Details

*   **Core Architecture:** State-of-the-art Deep Convolutional Neural Networks (utilizing architectures like ResNet/DenseNet pre-trained on chest radiology datasets) optimized with transfer learning.
*   **Deployment Interface:** Production-ready asynchronous **FastAPI** medical imaging endpoint capable of processing DICOM/PNG/JPG image payloads under 200ms.
*   **Evaluation Metrics:** Validated strictly using ROC-AUC scores, Confusion Matrices, and F1-scores to guarantee diagnostic accuracy, safety, and alignment with digital health standards.
