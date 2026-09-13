# Hi 👋, I'm Gourav Barnwal

### Computer Vision | Applied Machine Learning | Backend Engineering

Computer Science undergraduate focused on **Computer Vision, Applied Machine Learning, and production backend systems**. I enjoy building end-to-end systems that take ML models beyond experiments and turn them into usable, tested applications.

Currently focused on computer vision anomaly detection, AI-assisted developer tools, and reliable ML deployment.

---

## 🔭 What I'm Currently Working On

- Building **VISYN — Deep Visual Intelligence for Quality Inspection**, a production-oriented computer vision system for visual anomaly detection using pretrained CNN features, reference feature banks, calibrated thresholds, localization, FastAPI, Docker, and a deployed web interface
- Building **DevLens** — an AI-powered visual debugging assistant that reads errors from images, finds the responsible code, generates fixes and regression tests with an LLM, and verifies the generated test inside an isolated sandbox
- Interning at **DRDO DYSL (Young Scientist Laboratory), Bengaluru**, working on feature matching and image retrieval research across classical and deep-learning methods
- Working on **TickerPulse**, an ML/LLM-assisted financial data pipeline with React, FastAPI, PostgreSQL, and external financial APIs
- Strengthening Data Structures & Algorithms with interview-focused problem solving

---

## 🚀 Featured Projects

### VISYN — Deep Visual Intelligence for Quality Inspection

**Tech:** Python, PyTorch, OpenCV, FastAPI, React, TypeScript, Docker, MobileNetV3-Small

Production-oriented computer vision system for detecting visual defects by comparing new images against learned representations of normal samples.

- Uses **MobileNetV3-Small** as a lightweight production feature extractor
- Extracts intermediate visual features from **L4 and L8** and compares local feature representations against normal reference banks
- Uses category-specific **P99 thresholds** with a three-way decision system: **PASS / REVIEW / FAIL**
- Generates explanatory defect localization using feature-level anomaly maps and connected-component analysis
- Evaluated across **six industrial-style inspection categories**, achieving **0.9511 macro AUROC** and **0.9525 macro AP**
- Built a production inference engine with validated model artifacts, reference banks, configuration manifests, and threshold files
- Added CPU-oriented deployment optimizations, including **lazy loading of category-specific reference banks** to reduce cloud memory usage
- Exposed the model through a **FastAPI inspection API** with health checks, upload validation, error handling, and image-size protection
- Containerized the backend with Docker and deployed the inference service to Render
- Built and deployed a responsive React/TypeScript frontend with image upload, camera capture, inspection results, and defect localization
- Implemented end-to-end validation across model inference, API, frontend, deployment, and error-handling paths

**GitHub:** https://github.com/GouravBarnwal/VISYN  
**API:** https://visyn.onrender.com  
**Frontend:** https://visyn-chi.vercel.app

---

### DevLens — AI-Powered Visual Debugging Assistant

**Tech:** Next.js, FastAPI, Tesseract, OpenCV, Google Gemini API, DistilBERT, Sentence Transformers, Docker, E2B

- Reads programming errors from phone-camera images or pasted text using an adaptive multi-candidate OCR pipeline with rotation correction, denoising, thresholding, and ensemble scoring
- Finds the responsible code using exact filename matching, fuzzy matching, and semantic embedding-based search
- Uses an LLM to diagnose errors, generate fixes, and write regression tests
- **Actually executes the generated tests inside an isolated sandbox** instead of blindly trusting the LLM's output
- Fine-tuned a DistilBERT error-type classifier; diagnosed template-data overfitting and improved the pipeline using more diverse training data, reaching a defensible **82% accuracy**
- Maintains separate full and lightweight deployment versions to handle free-tier memory constraints explicitly

**GitHub:** https://github.com/GouravBarnwal/DevLens  
**Lite Version:** https://github.com/GouravBarnwal/DevLens-Lite  
**Live Demo:** https://dev-lens-lite.vercel.app/

---

### DRDO DYSL — Feature Matching & Image Retrieval Research

**Tech:** Python, OpenCV, PyTorch, SIFT, ORB, SuperPoint, SuperGlue, DISK, LightGlue, ALIKED, LoFTR, DeDoDe, RoMa, DINOv2

- Built a feature-matching and image-retrieval benchmarking pipeline on the TUM RGB-D dataset
- Compared classical and deep-learning-based feature methods under rotation, scale, and low-texture conditions
- Evaluated feature robustness using quantitative matching experiments
- Analyzed **DINOv2 embeddings** for image similarity and robustness
- Conducted top-3 image retrieval experiments across multiple matching approaches
- Produced a structured technical report with quantitative comparisons

---

### TickerPulse — Stock Trend & Sentiment Tracker

**Tech:** React, FastAPI, PostgreSQL

- Tracks stock mentions across influencers, news, and financial content
- Uses sentiment analysis to identify companies experiencing increased attention
- Triggers alerts for sudden changes in market interest
- Built the backend data flow around external financial APIs and PostgreSQL

**GitHub:** https://github.com/viswans435/tickerpulse/tree/main/src

---

### Deforestation Fire Classification — MODIS Satellite Data

**Tech:** Python, Scikit-learn, Streamlit, Pandas, NumPy

- Classified fire types using MODIS satellite data from 2021–2023
- Performed exploratory analysis of spatial patterns and class imbalance
- Built interactive visualizations and maps
- Deployed the ML application using Streamlit

**GitHub:** https://github.com/GouravBarnwal/Deforestation_Detection_Fire  
**Live App:** https://deforestation-fire-detection-grv.streamlit.app/

---

### Student Attendance Monitoring & Alert System

**Tech:** React, Flask, Firebase

- Built role-based dashboards for automated attendance management
- Added automated email alerts for attendance below configured thresholds
- Implemented OTP authentication
- Integrated SBI Collect payment workflows

**GitHub:** https://github.com/GouravBarnwal/Students-Attendance-Monitoring-and-Alert-Generation-System

---

## 🛠️ Languages & Technologies

### Computer Vision & Machine Learning
`Python` `PyTorch` `OpenCV` `Scikit-learn` `TensorFlow` `NumPy` `Pandas`

### AI & NLP
`Google Gemini` `Tesseract OCR` `Sentence Transformers` `DistilBERT` `DINOv2`

### Backend & Databases
`FastAPI` `Flask` `Django` `Node.js` `Express` `PostgreSQL` `MySQL` `MongoDB` `Firebase`

### Frontend
`React` `Next.js` `TypeScript` `JavaScript` `HTML5` `CSS3`

### Deployment & Engineering
`Docker` `AWS` `Git` `REST APIs` `Vercel` `Render`

### Programming
`Python` `Java` `C` `JavaScript` `TypeScript`

---

## 💼 Experience

### Intern — DRDO DYSL (Young Scientist Laboratory)
**Bengaluru**

- Computer vision research focused on feature matching, image retrieval, descriptor robustness, and deep visual representations
- Worked with classical and deep-learning-based feature extraction and matching methods
- Conducted quantitative benchmarking and experimental analysis

### AI/ML Intern — AICTE × Edunet × Shell

Applied machine learning to practical datasets and ML workflows.

### AI Software Engineer Intern — AI Product Manager Accelerator

Worked on AI/software engineering workflows and application development.

### Software Development Intern — NIAMT, Ranchi

Worked on software development and application engineering.

---

## 🎓 Education

### B.Tech — Computer Science & Engineering

**CGPA:** 7.27

---

## 📚 Currently Improving

- Data Structures & Algorithms
- Computer Vision
- Deep Learning
- ML System Design
- Backend Engineering
- Production ML Deployment

---

## 📫 Connect With Me

- **GitHub:** https://github.com/GouravBarnwal
- **LinkedIn:** https://linkedin.com/in/grv1404
- **Portfolio:** https://gouravs-portfolio.vercel.app
