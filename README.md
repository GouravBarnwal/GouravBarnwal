Hi 👋, I'm Gourav Barnwal
### Computer Vision | Applied Machine Learning | Backend Engineer

I am a Computer Science undergraduate with hands-on experience in building scalable full-stack applications and applying machine learning and computer vision to real-world data. I focus on writing clean, efficient code and solving problems with a strong foundation in data structures and algorithms.

---

### 🔭 What I'm Currently Working On

- Building **DevLens** — an AI-powered visual debugging assistant that reads errors from photos (OCR), diagnoses them, finds the actual buggy code in a project, generates a fix and test with an LLM, and verifies the fix by actually running the test in an isolated sandbox
- Interning at **DRDO DYSL (Young Scientist Laboratory), Bengaluru** — working on feature-matching and image-retrieval research (classical and deep-learning descriptors, robustness benchmarking, DINOv2 embedding analysis)
- Working on **TickerPulse** — implementing an LLM-assisted backend data ingestion pipeline, integrating external financial APIs, and resolving CORS issues between React and FastAPI while managing PostgreSQL data flow
- Strengthening Data Structures & Algorithms with interview-focused Medium problems
- Applying machine learning to real datasets such as satellite imagery, financial data, and synthetic error-classification data

---

### 🚀 Featured Projects

**DevLens — AI-Powered Visual Debugging Assistant**
Tech: Next.js, FastAPI, Tesseract/OpenCV, Google Gemini API, fine-tuned DistilBERT, sentence-transformers, Docker, E2B

- Reads an error from a phone camera photo or pasted text, using an adaptive multi-candidate OCR pipeline (rotation correction, denoising, thresholding, ensemble scoring across image variants)
- Finds the responsible code via exact filename match, fuzzy match, and semantic (embedding-based) search
- Uses an LLM to diagnose the error, generate a fix, and write a regression test — then actually **runs the generated test in a sandbox** to verify the fix works, rather than trusting the AI's output blindly
- Fine-tuned a DistilBERT classifier as an error-type fallback: an honest engineering story included two real iterations — the first attempt overfit to template data (fake ~100% accuracy that failed on new inputs), diagnosed and fixed with LLM-generated diverse training data, landing on a real, defensible 82% accuracy
- Deployed with a disclosed "Lite Mode" tradeoff on free-tier hosting (heavy ML libraries skipped in production due to memory limits, full feature set available locally) — a deliberate, documented engineering decision rather than a hidden limitation
- GitHub (full version): https://github.com/GouravBarnwal/DevLens
- GitHub (deployed lite version): https://github.com/GouravBarnwal/DevLens-Lite
- Live demo: https://dev-lens-lite.vercel.app/

**DRDO DYSL — Feature Matching & Image Retrieval Research**
Tech: Python, OpenCV, PyTorch, SIFT, ORB, SuperPoint+SuperGlue, DISK+LightGlue, ALIKED, LoFTR, DeDoDe, RoMa, DINOv2

- Built a full feature-descriptor benchmarking pipeline from scratch on the TUM RGB-D dataset (600+ frames), comparing classical (SIFT, ORB) and deep-learning-based (SuperPoint, DISK, LoFTR, RoMa) descriptors
- Ran robustness benchmarking across multiple conditions (rotation, scale, low texture) and produced a structured technical report with quantitative comparisons
- Analyzed DINOv2 CLS-token embeddings for image similarity and robustness
- Delivered top-3 image retrieval experiments comparing six matching algorithms for a multi-image reference/query task

**TickerPulse — Stock Trend & Sentiment Tracker**
Tech: React, FastAPI, PostgreSQL

- Tracks stock mentions from influencers, news, and financial content
- Performs sentiment analysis to rank trending companies
- Triggers alerts for sudden spikes in market interest
- GitHub: https://github.com/viswans435/tickerpulse/tree/main/src

**Deforestation Fire Classification (MODIS Satellite Data)**
Tech: Python, Scikit-learn, Streamlit

- Classified fire types using MODIS data (2021–2023)
- Performed EDA on spatial patterns and class imbalance
- Built interactive maps and deployed an ML application
- GitHub: https://github.com/GouravBarnwal/Deforestation_Detection_Fire.git
- Live App: https://deforestation-fire-detection-grv.streamlit.app/

**Student Attendance Monitoring & Alert System**
Tech: React, Flask, Firebase

- Automated attendance with role-based dashboards
- Email alerts for attendance below threshold
- OTP authentication and SBI Collect payment integration
- GitHub: https://github.com/GouravBarnwal/Students-Attendance-Monitoring-and-Alert-Generation-System.git

---

### 🛠️ Languages and Tools

`OpenCV` `PyTorch` `TensorFlow` `Scikit-learn` `Pandas` `Seaborn` `NumPy`
`Python` `JavaScript` `TypeScript` `Java` `C`
`React` `Next.js` `Node.js` `Express` `Django` `Flask` `FastAPI`
`PostgreSQL` `MySQL` `MongoDB` `Firebase`
`Docker` `AWS` `Git`
`HTML5` `CSS3` `Bootstrap` `Framer` `Unity`

---

### 📌 Experience Highlights

- **Intern, DRDO DYSL (Young Scientist Laboratory)** — Bengaluru, feature-matching & image-retrieval research, under Rahul Rai
- **AI/ML Intern — AICTE × Edunet × Shell**
- **AI Software Engineer Intern — AI Product Manager Accelerator**
- **Software Development Intern — NIAMT, Ranchi**

---

### 🎓 Education

**B.Tech in Computer Science & Engineering**
CGPA: 7.27

---

### 📫 Reach Me

- GitHub: https://github.com/GouravBarnwal
- LinkedIn: https://linkedin.com/in/grv1404
- Portfolio: https://gouravs-portfolio.vercel.app
