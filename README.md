# Priyan U

Third-year B.Tech student in AI & Data Science at Amrita Vishwa Vidyapeetham. I build machine learning systems for problems I see around me, in healthcare, farming, finance and small business, and I focus on getting models into real use rather than leaving them in notebooks.

## Shipped

**GPS FARM**: Android app for poultry and farm batch management. It replaces paper records with a phone-based system built for farmers with no technical background.

### 1. Rural Health Triage Assistant (Tamil / English, voice-based)
**Problem:** Village clinics often have one doctor for hundreds of patients, and people wait hours or travel far for problems that a nurse could sort out first.
**What I'm building:** A voice-enabled assistant that asks a patient about their symptoms in Tamil, checks them against public clinical guidelines using retrieval, and flags emergencies for immediate referral. It does not diagnose. It only helps decide who needs a doctor first.
**Tech:** Whisper speech recognition, RAG over ICMR/WHO guidelines, multilingual embeddings, FastAPI

### 2. Early Disease Warning for Poultry Farms from Sensor Data
**Problem:** Farmers usually notice disease after birds have already started dying, and by then the batch is lost.
**What I'm building:** A system that reads temperature, humidity, ammonia and feed-intake data from low-cost sensors and detects abnormal patterns early, so the farmer gets an alert before the outbreak spreads. It runs on a Raspberry Pi/ESP32 so it works without cloud access.
**Tech:** Time-series anomaly detection (LSTM autoencoder, Isolation Forest), ESP32 sensors, MQTT, Android alerts via GPS FARM

### 3. UPI Fraud Detection with Graph Neural Networks
**Problem:** Digital payment fraud in India is mostly organised. Fraudsters use networks of mule accounts that look harmless when each transaction is checked alone.
**What I'm building:** A model that treats accounts and transactions as a graph and finds suspicious clusters and rings, with explanations of why an account was flagged so that a human analyst can verify it.
**Tech:** PyTorch Geometric, GraphSAGE/GAT, imbalanced-data handling, SHAP/GNNExplainer
### 4. Crop Yield Estimation from Satellite Images for Small Farmers
**Problem:** Smallholder farmers have no reliable way to estimate yield before harvest, which makes insurance claims and loan decisions slow and unfair.
**What I'm building:** A model that estimates yield and crop stress at plot level from free Sentinel-2 satellite imagery and weather data, delivered through a simple map view.
**Tech:** Sentinel-2 / Google Earth Engine, CNN + temporal models, GeoPandas, rasterio

### 5. Invoice and Bill Understanding for Small Shops
**Problem:** Medical, stationery and hardware shops enter supplier bills into their accounts by hand, which is slow and full of mistakes.
**What I'm building:** A tool that reads a photo of a supplier bill and pulls out the items, quantities, prices and GST into structured data, then updates the shop's stock records.
**Tech:** Layout-aware document models (LayoutLM / vision-language model), OCR, fine-tuning on Indian invoice formats, FastAPI
## In progress
### 6. Pothole and Road-Damage Mapping from Dashcam Video
**Problem:** Road damage is reported late and by hand, so repairs are slow and accidents happen.
**What I'm building:** A detector that finds potholes in ordinary phone or dashcam video, tags each one with GPS, and builds a map that a municipality can use to prioritise repairs. It runs on-device so it doesn't need a constant connection.
**Tech:** YOLO, TFLite on Android, GPS tagging, map dashboard

## Skills

**Languages:** Python, SQL, Java, Kotlin, C++, JavaScript

**Machine Learning:** Supervised and unsupervised learning, feature engineering, model evaluation, hyperparameter tuning, time-series forecasting, anomaly detection, imbalanced-data handling

**Deep Learning:** PyTorch, TensorFlow/Keras, CNNs, RNN/LSTM, Transformers, transfer learning, graph neural networks (PyTorch Geometric)

**Generative AI & LLMs:** Hugging Face Transformers, RAG pipelines, LangChain, LangGraph, prompt engineering, fine-tuning (LoRA/QLoRA), embeddings, vector databases (FAISS, ChromaDB)

**Computer Vision:** OpenCV, YOLO, image classification, object detection, OCR, Grad-CAM explainability

**Speech & NLP:** Whisper, tokenization, multilingual text processing, text classification

**Data:** Pandas, NumPy, Matplotlib, Seaborn, Power BI, SQL (PostgreSQL, MySQL, SQLite), data cleaning and visualization

**MLOps & Deployment:** FastAPI, Docker, Git/GitHub, GitHub Actions, MLflow, Weights & Biases, model quantization (TFLite)

**Mobile & Edge:** Android development, Raspberry Pi, ESP32, MQTT

**Tools:** Jupyter, Google Colab, Kaggle, VS Code, Linux command line

**Core Strengths:** Problem solving, data structures and algorithms, turning real-world problems into working ML systems
