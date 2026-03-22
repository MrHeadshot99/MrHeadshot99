### 👋 Hi, I'm Subin Kim

Ph.D. student in Computer Science at **Utah State University**, focusing on **applied machine learning for computer vision and sensor data**  
(e.g., **UAV hyperspectral imaging**, **3D CT medical imaging**).

I enjoy turning ambiguous real-world problems into **end-to-end ML pipelines**:

- framing the use case and evaluation metrics  
- structuring noisy, high-dimensional data  
- building and tuning ML/DL models in Python  
- delivering **reproducible, metric-driven proof-of-concepts**.

Currently exploring **HSI for crop disease detection**, and **LLM-based AI systems architecture**.

  </td>
  </tr>
</table>

---

## 🧠 Research & Technical Interests

### 🔍 Recent Research
- 🌾 **Agricultural Computer Vision** – UAV hyperspectral imaging, plant disease detection, band selection

### 📚 Previous Research and Project History
- 🖼️ **Image & Video Forensics** – deepfake detection with traditional ML
- 🧬 **Medical Imaging** – 3D CT fracture detection, preprocessing pipelines and baselines
- 📊 **Structured Data ML** – tabular modeling for real-estate and intrusion detection

### 🛠️ Techniques I'm Currently Learning
- 🧩 **AI Systems & LLMs** – foundation models, RAG, deployment-aware architectures

---

## 🛠 Skills

**Languages & Tools**  
`Python` · `Git` · `Linux` · `Jupyter / Colab` · `Conda`

**ML / DL / CV**  
`PyTorch` · `TensorFlow / Keras` · `scikit-learn` · `OpenCV`

**Data Work**  
`Data wrangling` · `Feature engineering` · `Cross-validation` · `Model evaluation` · `Error analysis`

**LLMs & AI Systems**  
Currently taking **graduate-level coursework** on LLMs and AI system architecture  
(Foundation models, prompting, RAG concepts, deployment basics) and built a **small toy RAG prototype** with an open-source LLM.

---

## 🎓 Education

**Utah State University, School of Computing** · *Logan, UT*  
Ph.D. in Computer Science (**M.S. in Computer Science en route, expected May 2026**)  
GPA: **3.62 / 4.0**

**Relevant Coursework**

- **Machine Learning & AI**  
  Machine Learning for Data Science · Deep Learning Theory & Applications · Computer Vision  
- **Data & Systems**  
  Data Mining · Introduction to Data Analysis · Computer Networks & Security  
- **AI Systems & Foundation Models**  
  AI System Architecture (in progress) · AI in Education (in progress)

---

**Gyeongsang National University** · *Jinju-Si, Republic of Korea*  
B.S. in Mechanical Engineering (March 2017 – August 2023)

---

## 📂 Selected Projects

### 1. Dual-Branch HSI Wheat Rust Classifier (Individual Ph.D. Research)  
*Utah State University — ICPR 2026 submission under review*  

- Headed an independent project designing a **dual-branch spectral–spatial CNN** (2D ResNet-18 + 1D CNN) with a SAPFB fusion block and physics-aware band selection, reducing spectral dimensionality by **125 → 7 bands** while stabilizing labels via NDVI-based refinement.  
- Achieved **85.19% overall accuracy** on the ICPR 2024 wheat-rust benchmark, surpassing strong CNN/Transformer/Mamba baselines and outperforming **MambaHSI** by **4.6 percentage points**.

---

### 2. Lightweight Deepfake Detector (Course Project – ML Lead)  
*STAT 6685 Deep Learning & CS 6680 Computer Vision, Utah State University*  

- Formulated a **lightweight deepfake detection pipeline** combining **6+ handcrafted feature families**  
  (LBP, wavelet, quality & frequency-domain features, color statistics) with an **RBF-SVM** as ML lead in a team project.  
- Delivered **0.71 F1-score** on the FaceForensics++ DeepFakes subset and **0.77 accuracy** on the CIDAUT dataset with a stacking ensemble, coming within **2–5 percentage points** of ResNet-50 / EfficientNet-B0 baselines while using significantly fewer parameters.

---

### 3. 3D CT Spine Fracture Baseline (Individual Course Project)  
*CS 5080 Data Mining — RSNA 2022 Cervical Spine Fracture Detection*  

- Automated a **4-stage 3D CT preprocessing pipeline** for the RSNA 2022 cervical spine fracture dataset:
  DICOM loading, HU windowing/normalization, isotropic resampling, and patch-based 3D volume extraction with on-the-fly augmentation.  
- Established a **patch-based 3D ResNet-18 multi-label classifier** over 8 output labels (patient\_overall, C1–C7) with patient-level 3-fold cross-validation and early stopping, and analyzed failure modes to propose **5 concrete improvements** for future SOTA-level models.

---

### 4. Zillow Zestimate Error Predictor (Course Project)  
*CS 5665 Machine Learning for Data Science, Utah State University*  

- Built an **end-to-end regression pipeline** using Zillow public data to predict future home sale prices and estimate Zestimate error.  
- Performed feature engineering on temporal, geographic, and property attributes; handled missing data and skewed targets.  
- Trained and compared **XGBoost, Random Forest, and regularized linear models**, targeting log-error minimization and robust generalization across time.

---

### 5. Data Quality and Evaluation Strategies for Intrusion Detection  
*A Comparative Study of CIC-IDS2017 and BCCC-CIC-IDS2017 — CS 6215 Computer Networks & Security*  

- Examined **data quality, label issues, and evaluation protocols** across CIC-IDS2017 and BCCC-CIC-IDS2017 intrusion detection datasets.  
- Implemented preprocessing pipelines (feature selection, rebalancing, train/val/test splits) and evaluated ML classifiers under multiple metrics to highlight the impact of noisy labels and dataset shifts on IDS performance.  
- Proposed **guidelines for fair benchmarking** of IDS models, emphasizing realistic traffic distributions and robust metrics beyond accuracy.

---

## 💼 Experience

**Graduate Teaching Assistant**  
*School of Computing, Utah State University* · Logan, UT · *Aug 2024 – Present*  

- Supported **30+ students per semester** across Intro CS, Computer Architecture, and NLP by running weekly office hours and review sessions, grading programming assignments, and clarifying ML and systems concepts.

---

**Undergraduate Research Assistant / Winter Research Intern**  
*Intelligence and Interactive Robotics Lab, GNU* · Jinju-Si, Republic of Korea · *Jul 2023 – Dec 2023*  

- Led the simulation unit in a project on **robotic orthosis control for mobility assistance**, linking OpenSim-based reinforcement learning environments with musculoskeletal models.

---

**Undergraduate Research Assistant**  
*Safe Search Lab, GNU* · Jinju-Si, Republic of Korea · *Sep 2022 – Jan 2023*  

- Assisted with development and testing of a **1/10-scale F1Tenth autonomous driving platform** in a Linux environment for a national academic competition.

---

## 🏆 Awards & Patents

- **Patent Application (Republic of Korea)**  
  “Novel Concept of Liquid Level Sensor using Distributed Optical Fiber Sensor with High Spatial Resolution”,  
  KR10-2023-0192798 (Dec 2023).  

- **Second Prize (Sonnet.ai Proprietor Award)**  
  The 1st F1Tenth Korea Championship, 2022, KSMTE, Republic of Korea.
  <img width="598" height="457" alt="image" src="https://github.com/user-attachments/assets/6a1e2386-ab89-4089-9ae2-c9179654991e" />
  

- **Second Prize (College of Engineering Dean’s Award)**  
  2022 GNU Creative Challenge Design-Based Idea Competition, Gyeongsang National University.

---

## 📜 Earlier Projects (Selected)

- **Ankle Mobility Assistance Robot via RL** (2023)  
  Initiated concept and environment setup for a robotic orthosis controller using OpenSim + OpenSim-RL and PPO to assist patients with impaired mobility.

- **Reinforcement Learning in Atari Pong / Cartpole**  
  Course project implementing and tuning **PPO** for Atari Pong and classic control tasks.  
  Repo: [Reinforcement-Learning-in-Atari-game-Pong\_v0](https://github.com/MrHeadshot99/Reinforcement-Learning-in-Atari-game-Pong_v0)

- **Dice Game (TkInter)**  
  Simple Python game where a user and computer roll dice to move along a board.  
  Repo: [Dice-game](https://github.com/MrHeadshot99/Dice-game)

---

## 🌱 English Proficiency

- TOEFL iBT (Home Edition): **85**  
- Duolingo English Test: **115**

---

> _“I like models that not only perform well on benchmarks,  
> but also make sense with the data and constraints of the real world.”_

