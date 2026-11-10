<div align="center">

# Venu Bandi

**MS Data Science · UMBC**

I build production-quality ML systems — end-to-end, from raw data to deployed models.<br>
Computer vision · Healthcare AI · Edge AI · Intelligent agents

[![GitHub followers](https://img.shields.io/github/followers/VenuBandi?style=social)](https://github.com/VenuBandi)

</div>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

**[CDC Chronic Health Risk Model](https://github.com/VenuBandi/cdc-chronic-health-risk)**

Predicts 10 chronic disease rates across **73,000+ U.S. census tracts** (R² 0.86–0.98). Phase 2 uses a PyTorch neural network to produce a composite risk index — visualized on a [live interactive map](https://venubandi.github.io/cdc-chronic-health-risk/).

`PyTorch` `scikit-learn` `Folium` `CDC PLACES 2024`

</td>
<td width="50%" valign="top">

**[Structural Crack Detection](https://github.com/VenuBandi/structural-crack-detection)**

Transfer learning on 56,092 infrastructure images. ResNet50 · DenseNet121 · EfficientNet-B0 benchmarked on SDNET2018. EfficientNet-B0 wins at **92.5% accuracy, 0.848 recall**, tuned to minimize missed cracks in safety-critical inspection.

`PyTorch` `torchvision` `EfficientNet` `SDNET2018`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Histopathologic Cancer Detection](https://github.com/VenuBandi/histopathologic-cancer-detection)**

Custom CNN vs DenseNet121 on 5,000 H&E tissue patches. DenseNet121 achieves **89% accuracy and ROC-AUC 0.9625**. Full optimizer × scheduler × augmentation grid experiments.

`PyTorch` `torchvision` `DenseNet121` `Kaggle`

</td>
<td width="50%" valign="top">

**[Silent Signal](https://github.com/VenuBandi/silent-signal)**

Real-time emergency gesture recognition — MediaPipe keypoints + Motion BiLSTM on a custom-recorded 9-class dataset. Danger F1 = 0.91, **2,563 FPS inference**.

`PyTorch` `MediaPipe` `LSTM` `OpenCV`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Gaming Stock Prediction](https://github.com/VenuBandi/gaming-stock-prediction)**

Apache Spark GBT pipeline predicting next-day close prices for 22 gaming stocks across **334,405 rows**. Test R² = 0.9629. Predictions stored in MongoDB; Gradio dashboard for live exploration.

`PySpark` `Spark ML` `MongoDB` `Gradio` `yfinance`

</td>
<td width="50%" valign="top">

**[FlightOps AI](https://github.com/VenuBandi/flightops-ai)**

Real-time flight delay recovery decision support for airline operations. R7 ensemble (LGB + Neural) — **MAE 8.3 min, 0.15 ms CoreML inference**. 22 AI models across 7 providers.

`Python` `LightGBM` `CoreML` `FastAPI` `Supabase`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Keypoints Spidy Vision](https://github.com/VenuBandi/Keypoints_spidy_vision)**

Real-time human keypoint detection on NVIDIA Jetson, streamed to a live Flask dashboard. Forms the perception base for the gesture and anomaly detection systems.

`Python` `OpenCV` `NVIDIA Jetson Inference` `Flask`

</td>
<td width="50%" valign="top">

**[Spiderman Anomaly Detection](https://github.com/VenuBandi/spiderman-anomaly-detection)**

Rule-based anomaly detection on NVIDIA Jetson — SSD-Mobilenet-v2 detects forbidden objects and crowd violations, triggering real-time alerts on a live cyberpunk dashboard.

`Python` `Flask` `OpenCV` `NVIDIA Jetson Inference`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Real-Time Gesture Recognition](https://github.com/VenuBandi/real-time-gesture-recognition-system)**

V1 prototype: 2-class (HELP / DANGER) gesture LSTM on MediaPipe hand keypoints. **~1,979 FPS inference.** Predecessor to Silent Signal — extended to 9 classes and full-body keypoints.

`PyTorch` `MediaPipe` `LSTM` `OpenCV`

</td>
<td width="50%" valign="top" style="vertical-align: top;">

**[Jarvis Assistant](https://github.com/VenuBandi/jarvis-assistant)**

Always-on personal AI for macOS. Hotkey → local whisper.cpp STT → multi-brain routing (Ollama · Claude · Gemini Flash) → spoken reply. Every action classified by risk tier and enforced in code.

`Python` `FastAPI` `Ollama` `whisper.cpp` `MediaPipe`

</td>
</tr>
</table>

---

<div align="center">

**Languages & Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

<br>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=VenuBandi&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=VenuBandi&layout=compact&theme=dark&hide_border=true)

</div>
