<h1 align="center">Amin Baiju</h1>
<p align="center">
  <b>Data Scientist · NLP & Multilingual ML · Geospatial Analytics</b><br>
  MSc Data Science, AI & Digital Business (Gisma, Berlin, 2026) · Open to Data Science / ML / NLP roles, Berlin or remote
</p>

<p align="center">
  <a href="https://linkedin.com/in/amin-baiju"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:aminbaiju@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Berlin,_Germany-555555?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Berlin">
</p>

---

### About me

I build NLP and geospatial models and care about whether they can be trusted, not only how accurate they look. My MSc thesis showed that multilingual language models can be close to chance on a language while reporting over 90% confidence, and I now treat calibration and failure analysis as part of every evaluation.

I speak Malayalam, Tamil, Hindi and English (plus basic German), which is a large part of why multilingual NLP interests me. Before data science I studied English literature and worked in narrative filmmaking, so I put real effort into explaining results clearly to non-technical people.

---

### Featured work

#### [Cross-Lingual Transfer Failure Modes](https://github.com/wckd6174/crosslingual-transfer-failure-modes) · MSc thesis
**Question:** When a multilingual model is fine-tuned on English, how and why does it fail on other languages?
- Proposed a 12-mode failure taxonomy and measured it on 4 models (XLM-R, mBERT, BanglaBERT, GBERT) across English, German and Bengali.
- Zero-shot transfer lost **~2× more macro-F1 on Bengali than on German** for both multilingual models.
- Found **silent calibration failure**: mBERT on Bengali sits at chance (macro-F1 0.50) with 92% average confidence; GBERT sees 95% unknown tokens on Bengali yet predicts at 98% confidence.
- Turned the findings into a pre-deployment checklist: tokenizer coverage, ECE, and comparison against a monolingual baseline.

`Python` `PyTorch` `Hugging Face Transformers` `scikit-learn` `Google Colab (T4)`

#### [Riyadh Urban Canopy & Heat Analysis](https://github.com/wckd6174/riyadh-urban-canopy)
**Question:** Where in Riyadh would new greenery reduce heat the most?
- Fused Sentinel-2 NDVI, Landsat 8/9 land-surface temperature and ESA WorldCover into a planting-priority map.
- Measured **+27% vegetation cover (2019–2025)** and identified **246 km² of high-priority planting zones**.

`Google Earth Engine` `Sentinel-2` `Landsat` `Python`

#### [El Niño Teleconnections & Rainfall Prediction](https://github.com/wckd6174/enso-teleconnections)
**Question:** How does El Niño reshape rainfall worldwide, and can it be predicted regionally?
- Reproduced the canonical El Niño rainfall patterns from raw NOAA ERSSTv5 and GPCP data.
- A model trained **without** the 2015/16 super El Niño still anticipated its rainfall pattern (DJF correlation up to 0.91).
- Showed where it fails: it gets timing right but under-predicts extremes, and skill fades away from the Pacific.

`xarray` `Cartopy` `scikit-learn` `Python`

---

### More projects

| Project | What it does | Stack |
|---|---|---|
| [Mental Health Detection (NLP)](https://github.com/wckd6174/mental-health-nlp-detection) | Benchmarks BERT/RoBERTa against LSTM baselines for detecting depressive language in social-media posts | BERT, RoBERTa, LSTM, PyTorch |
| [Airline Passenger Satisfaction](https://github.com/wckd6174/airline-satisfaction-classifier) | Classifies satisfaction and ranks service drivers; 96% test accuracy, in-flight Wi-Fi identified as a top driver | Random Forest, GridSearchCV |
| [Telecom Churn Prediction](https://github.com/wckd6174/telecom-churn-prediction) | Recall-focused churn model to flag at-risk customers for retention | XGBoost, SMOTE, scikit-learn |

---

### Toolkit

| | |
|---|---|
| **Languages** | Python, SQL |
| **ML / DL** | PyTorch, TensorFlow, scikit-learn, XGBoost |
| **NLP** | Hugging Face Transformers, multilingual encoders, model calibration (ECE, Brier) |
| **Geospatial & climate** | Google Earth Engine, GeoPandas, xarray, Cartopy |
| **Data & BI** | pandas, NumPy, Power BI, Tableau |
| **Cloud** | AWS, GCP |

---

### Education
- **MSc Data Science, AI & Digital Business**, Gisma University of Applied Sciences, Berlin (2026)
- **BA English Literature**, Dr. Palpu College of Arts and Science, Kollam (2019–2022)
