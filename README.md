# Hi there, I'm Amin! 👋

## Machine Learning Engineer | NLP & Geospatial Analytics | Data Scientist

I am MSc Data Science graduate based in Berlin bridging the gap between raw data and intelligent decision-making. I specialize in building robust **NLP pipelines**, **predictive models**, and **geospatial analyses** that solve real-world problems across business, healthcare, and urban planning.

-  Completed my MSc thesis on cross-lingual transfer failure modes in multilingual language models (XLM-R, mBERT, BanglaBERT, GBERT)
-  Recently published a satellite-based **Urban Canopy & Heat Analysis** of Riyadh using Google Earth Engine
-  Authored research on **Mental Health Detection using BERT & RoBERTa**
-  Open to roles in ML/AI, Data Science, and Geospatial Analytics

---

## Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black)
![Google Earth Engine](https://img.shields.io/badge/Google_Earth_Engine-4285F4?style=for-the-badge&logo=google-earth&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139CD8?style=for-the-badge&logoColor=white)

---

## Featured Projects

### 🌐 [Cross-Lingual Transfer Failure Modes (MSc Thesis)](https://github.com/wckd6174/crosslingual-transfer-failure-modes)
Master's dissertation proposing a 12-mode failure-mode taxonomy for cross-lingual transfer in multilingual encoders, tested on English, German and Bengali sentiment classification.
- **Tech:** XLM-RoBERTa, mBERT, BanglaBERT, GBERT, Hugging Face Transformers, PyTorch.
- **Impact:** Showed zero-shot transfer loses ~2× more macro-F1 on Bengali than on German for both multilingual models (gap to monolingual ceiling: 0.24 vs 0.11 for XLM-R).
- **Highlight:** Exposed silent calibration failure. mBERT on Bengali sits at chance-level macro-F1 (0.50) with 92% average confidence, and GBERT sees 95% UNK tokens on Bengali yet still predicts at 98% confidence.

### 🌍 [Riyadh Urban Canopy & Heat Analysis](https://github.com/wckd6174/riyadh-urban-canopy)

*Satellite-derived priority map for urban greening interventions in Riyadh.*

- **Tech:** Google Earth Engine, Sentinel-2, Landsat 8/9, ESA WorldCover, Python.
- **Impact:** Quantified **+27% vegetation cover growth** (2019–2025) and identified **246 km² of high-priority planting zones** — a 2.5× expansion envelope on current canopy.
- **Highlight:** Multi-sensor fusion (optical NDVI + thermal LST + land-cover masking) producing planning-ready intervention zones.

### 🌊 [El Niño Global Teleconnections & Rainfall Prediction](https://github.com/wckd6174/enso-teleconnections)
End-to-end climate analysis mapping how El Niño reorganises rainfall worldwide, with a validated regional prediction model.
- **Tech:** xarray, Cartopy, Scikit-learn, NOAA ERSSTv5 & GPCP, Python.
- **Impact:** Reproduced every canonical El Niño teleconnection from raw data; a model trained excluding the 2015/16 super-El-Niño still anticipated its rainfall pattern (DJF correlation up to 0.91).
- **Highlight:** Diagnosed that the model captures rainfall *timing* but under-predicts *extreme magnitude* — and that ENSO skill decays from the Pacific core outward, weakest where the Indian Ocean Dipole dominates.
  
### 🧠 [AI-Powered Mental Health Detection (NLP)](https://github.com/wckd6174/mental-health-nlp-detection)

*Authored research benchmarking Transformer models against Deep Learning baselines.*

- **Tech:** BERT, RoBERTa, LSTM, PyTorch.
- **Impact:** Achieved **>99% accuracy** in detecting depressive language on social media.
- **Highlight:** Addressed ethical AI challenges and data bias.

### ✈️ [Airline Passenger Satisfaction Prediction](https://github.com/wckd6174/airline-satisfaction-classifier)

*End-to-end classification pipeline identifying key service differentiators.*

- **Tech:** Random Forest, GridSearch, Feature Importance Analysis.
- **Impact:** Achieved **96% Test Accuracy** and identified In-flight Wi-Fi as a top ROI driver.

### 📞 [Telecom Customer Churn Prediction](https://github.com/wckd6174/telecom-churn-prediction)

*Predictive system to support data-driven retention strategies.*

- **Tech:** XGBoost, SMOTE (Class Imbalance), Scikit-learn.
- **Impact:** Optimized model for **Recall** to capture high-risk customers for intervention.
