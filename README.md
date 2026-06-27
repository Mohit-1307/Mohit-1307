<div align="center">

<h1>MOHIT SINGH RAJPUT</h1>

<p><strong>Machine Learning Engineer &nbsp;·&nbsp; Applied AI Engineer &nbsp;·&nbsp; End-to-End ML Systems</strong></p>

<p>I design, build, and ship machine learning systems — from raw data to production — with a focus on reliability, reproducibility, and measurable impact.</p>

<p>
  <a href="https://linkedin.com/in/mohitsingh1307">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://www.kaggle.com/mohitsinghrajput1307">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/u/MOHIT_SINGH_RAJPUT/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
  </a>
  <a href="mailto:mohitsinghdausa@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=Mohit-1307&label=Profile%20Views&color=0e75b6&style=flat"/>

</div>

---

## About

I am a Machine Learning Engineer who works across the complete ML lifecycle — data acquisition, feature engineering, model development, evaluation, deployment, monitoring, and iteration. I treat machine learning as a software engineering discipline, not an experimentation exercise. That means reproducible pipelines, maintainable code, and systems that hold up under real-world conditions.

My current focus sits at the intersection of classical ML, deep learning, and production-grade Generative AI — particularly agentic systems with LangGraph, RAG pipelines, LLM evaluation, and scalable inference.

---

## Technical Stack

| Domain | Technologies |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) |
| **Machine Learning** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square&logo=xgboost&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-02AFEE?style=flat-square&logo=lightgbm&logoColor=white) |
| **Deep Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) |
| **Generative AI & LLMs** | ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) |
| **NLP** | ![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![NLTK](https://img.shields.io/badge/NLTK-3F7CAC?style=flat-square&logo=python&logoColor=white) |
| **Computer Vision** | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |
| **Data & Analytics** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white) |
| **MLOps & Deployment** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6600?style=flat-square&logo=databricks&logoColor=white) |

---

## Featured Projects

### AI Agents & RAG Systems with LangGraph

**[Repository →](https://github.com/Mohit-1307/AI-Agents-and-RAG-Systems-with-LangGraph)**

A structured, production-oriented implementation of agentic AI workflows using LangGraph — covering stateless graphs through multi-agent coordination and RAG pipelines, with full local execution via Ollama.

**Approach:**
- Built a phased learning and implementation path: stateless bot agents → persistent memory agents → conditional routing → ReAct tool-use → multi-agent coordination → RAG pipelines
- Implemented `bot_agent`, `memory_agent`, `sequential_agent`, `conditional_agent`, `react_agent`, `looping_agent`, and `drafter_agent` as self-contained, progressively complex modules
- Built a RAG pipeline (`rag_agent.py`) with ChromaDB as the vector store and Ollama (`mxbai-embed-large`) for local embeddings — no external API required
- Designed all agents around LangGraph's `StateGraph` paradigm with explicit node/edge wiring and shared state management

**Stack:** `Python` · `LangGraph` · `LangChain` · `Ollama` · `ChromaDB` · `Jupyter`

---

### Emotion Recognition from Speech

**[Repository →](https://github.com/Mohit-1307/CodeAlpha_EmotionRecognitionFromSpeech)**

Deep learning system for classifying speech emotion from audio using MFCC feature extraction and a CNN model trained on the RAVDESS dataset, with a real-time Streamlit interface.

**Approach:**
- Extracted MFCC (Mel-Frequency Cepstral Coefficient) features from audio using Librosa as the primary signal representation
- Trained a CNN to classify eight emotions from the RAVDESS dataset: Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised
- Separated training (`train.py`), inference (`predict.py`), utilities (`utils.py`), and label mapping (`labels.py`) into distinct modules for maintainability
- Deployed a Streamlit app supporting real-time audio upload and emotion prediction with confusion matrix and training curve visualizations

**Stack:** `Python` · `TensorFlow` · `Keras` · `Librosa` · `Scikit-learn` · `Streamlit`

---

### Heart Disease Prediction from Medical Data

**[Repository →](https://github.com/Mohit-1307/CodeAlpha-DiseasePredictionfromMedicalData)**

End-to-end supervised ML pipeline for heart disease risk classification using 13 clinical features from the UCI Heart Disease dataset, with a real-time Streamlit inference interface.

**Approach:**
- Performed EDA with correlation heatmaps, distribution plots, and statistical summaries across 13 clinical features
- Applied StandardScaler normalization and handled missing values before model training
- Trained and compared three classifiers — Logistic Regression, Random Forest, and SVM — evaluated across Accuracy, Precision, Recall, F1, and ROC-AUC
- Serialized the best model and fitted scaler with Joblib for consistent production inference
- Deployed an interactive Streamlit app for real-time patient risk prediction

**Stack:** `Python` · `Scikit-learn` · `Pandas` · `NumPy` · `Matplotlib` · `Streamlit` · `Joblib`

**Key Results:**
- Random Forest achieved 88–92% accuracy with the strongest ROC-AUC, selected as the deployment model
- ROC-AUC used as the primary metric over accuracy to handle class imbalance in medical data

---

### Handwritten Character Recognition — CNN

**[Repository →](https://github.com/Mohit-1307/CodeAlpha-HandwrittenCharacterRecognition)**

CNN-based digit recognition system trained on MNIST with a robust OpenCV preprocessing pipeline for real-world image normalization and a Streamlit inference interface.

**Approach:**
- Designed a custom CNN: two Conv2D + ReLU + MaxPool blocks followed by a 128-unit dense layer and 10-class Softmax output
- Built a multi-stage OpenCV preprocessing pipeline: grayscale → Gaussian blur → adaptive thresholding → morphological dilation → contour detection → crop → resize to 28×28 → normalize
- Trained on 60,000 MNIST images, evaluated on 10,000 held-out test samples
- Deployed as a Streamlit web app returning digit prediction and confidence score from uploaded images

**Stack:** `Python` · `TensorFlow` · `Keras` · `OpenCV` · `NumPy` · `Matplotlib` · `Streamlit`

**Key Results:**
- ~99% test accuracy on MNIST
- Preprocessing pipeline handles varied real-world inputs (different sizes, backgrounds, lighting conditions) before inference

---

### Shopper Spectrum — Customer Segmentation & Product Recommendations

**[Repository →](https://github.com/Mohit-1307)**

End-to-end unsupervised ML pipeline for e-commerce customer segmentation using RFM analysis and four clustering algorithms, paired with collaborative filtering and TF-IDF content-based recommendations, deployed as a Streamlit app.

**Approach:**
- Built an RFM (Recency, Frequency, Monetary) pipeline to extract behavioral signals from raw transaction data
- Applied and compared KMeans, Agglomerative Hierarchical, GMM, and DBSCAN — evaluated using silhouette score, Davies-Bouldin index, and Calinski-Harabasz index
- Implemented user-based collaborative filtering for product recommendations and TF-IDF content-based filtering for cold-start scenarios
- Deployed a Streamlit app with live segmentation outputs and synchronized model artifacts

**Stack:** `Python` · `Scikit-learn` · `Pandas` · `Matplotlib` · `Seaborn` · `Streamlit` · `Pickle`

**Key Outcomes:**
- Identified distinct, interpretable customer segments (Champions, Loyal, At-Risk, Lost) with verified cluster-segment mapping
- Full notebook audit cycle catching and correcting real errors — inverted cluster mapping, row count discrepancy, overstated diagnostic claim

---

### Flipkart CSAT Prediction

**[Repository →](https://github.com/Mohit-1307)**

Supervised classification pipeline for predicting customer satisfaction scores from Flipkart support interaction data to enable proactive service quality management.

**Approach:**
- Performed structured EDA and feature engineering on support interaction records
- Applied preprocessing including categorical encoding, feature scaling, and class imbalance handling
- Benchmarked multiple estimators including XGBoost with cross-validated performance metrics

**Stack:** `Python` · `Scikit-learn` · `XGBoost` · `Pandas` · `Matplotlib` · `Seaborn`

---

## Engineering Principles

**Reproducibility.** Experiments are versioned, documented, and repeatable. Results that cannot be reproduced are not results.

**Data quality first.** A clean, well-understood dataset consistently outperforms a complex model on poor data. Most production failures are data failures.

**Maintainability.** Code is written to be extended and debugged by someone else — including future me — not just to pass evaluation.

**Interpretability.** A model that cannot be explained cannot be trusted. Stakeholder adoption depends on understanding model behavior, not just accuracy numbers.

**Responsible AI.** Fairness, transparency, and unintended consequences are engineering concerns, not afterthoughts.

---

## Current Focus

- Agentic AI system design with LangGraph and LangChain
- Production-ready RAG pipelines and LLM evaluation frameworks
- MLOps best practices — CI/CD for ML, model monitoring, drift detection
- Scalable AI infrastructure and efficient model serving

---

## Learning Roadmap

- Advanced MLOps and CI/CD for ML workflows
- Distributed training and inference at scale
- LLM fine-tuning and alignment techniques
- Model monitoring and observability in production
- Cloud-native ML architectures on AWS and Azure

---

## GitHub Analytics

<div align="center">
<img height="120em" src="https://github-readme-stats.vercel.app/api?username=Mohit-1307&show_icons=true&hide_border=true&rank_icon=github&theme=nord"/>
<img height="120em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohit-1307&layout=compact&hide_border=true&theme=nord"/>
</div>
<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Mohit-1307&hide_border=true&theme=nord"/>
</div>

---

## Open to Collaboration

I am actively looking to contribute to and collaborate on:

- Machine learning engineering projects with real-world deployment requirements
- Open-source AI tools and ML infrastructure
- NLP, computer vision, and generative AI applications
- Agentic AI systems and research-to-production workflows

If you are building impactful AI systems or need an engineer who can take a project from data to deployment, reach out.

---

<div align="center">

**Let's connect**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohitsingh1307)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/mohitsinghrajput1307)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mohitsinghdausa@gmail.com)

</div>
