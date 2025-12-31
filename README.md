# 🧠 Gesture Analysis for Physiotherapy Rehabilitation Using Skeleton Data

## 📌 Project Overview
This project focuses on **analyzing and visualizing human body gestures for physiotherapy rehabilitation** using **skeleton-based motion data**. The goal is to support **physiotherapists and rehabilitation monitoring systems** by automatically organizing, visualizing, and evaluating patient movements as **correct or incorrect** during therapy exercises.

The work is implemented using **Python and Jupyter Notebooks** and is designed for **data visualization, motion analysis, and preliminary gesture correctness evaluation**, rather than sports analytics.

---

## 🎯 Objectives
- Organize raw skeleton motion files based on **body position** (standing, sitting, wheelchair, other)
- Extract **metadata** from file names for structured analysis
- Visualize **human skeletal motion** in 2D with labeled joints
- Analyze multiple **gesture classes (0–8)** used in rehabilitation
- Distinguish **correct vs incorrect** gesture executions
- Provide a clear visualization framework for **physiotherapy assessment**

---

## 📂 Dataset Description
- Input data consists of `.txt` files containing **3D joint coordinates**
- Each file represents a **sequence of skeleton frames**
- Filenames encode metadata such as:
  - Subject ID
  - Gesture label
  - Repetition number
  - Correct / Incorrect label
  - Body position (standing, sitting, wheelchair)

Example filename:101_18_0_1_1_stand.txt


---

## 🗂️ Data Preprocessing & Organization
The project automatically:
- Scans all skeleton `.txt` files
- Extracts body position using **regular expressions**
- Categorizes files into:
  - `standing`
  - `sitting`
  - `wheelchair`
  - `other`
- Generates **CSV files** listing filenames for each category
- Creates a **metadata CSV** with structured fields for further analysis

This ensures the dataset is **clean, structured, and analysis-ready**.

---

## 🦴 Skeleton Visualization
Key visualization features:
- 2D skeleton animation using **Matplotlib**
- Clearly labeled joints (head, spine, arms, legs)
- Consistent skeletal connections across frames
- Animated motion playback for each gesture
- Visual distinction:
  - 🟢 **Green** → Correct gesture
  - 🔴 **Red** → Incorrect gesture

Animations help in visually understanding **movement quality and posture correctness** during rehabilitation exercises.

---

## 🤖 Gesture Analysis
- Supports **9 gesture classes (GestureLabel 0–8)**
- For each gesture:
  - Multiple samples are visualized
  - Correctness is evaluated using metadata
- Helps identify **common incorrect movement patterns**
- Useful for **qualitative assessment** rather than clinical diagnosis

---

## 🛠️ Technologies Used
- **Python**
- **Jupyter Notebook / Google Colab**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Regular Expressions**
- **Git & Git LFS** (for large notebooks)

---

## 📄 Project Files
- `visualization.ipynb` – Data organization and skeleton visualization
- `classification.ipynb` – Gesture-wise analysis and correctness evaluation
- `visualization.ipynb.pdf` – Exported visualization notebook (for GitHub viewing)
- `classification.ipynb.pdf` – Exported analysis notebook (for GitHub viewing)

> 📌 Note:  
> The original notebooks are large and stored using **Git LFS**.  
> GitHub may not render them directly. Please refer to the **PDF versions** or download the notebooks locally to view full outputs.

---

## 🧩 Application Domain
- Physiotherapy rehabilitation monitoring
- Assistive healthcare analytics
- Movement quality assessment
- Skeleton-based human motion analysis
- Academic and research-oriented ML visualization

---

## 🚀 Future Enhancements
- Integration of machine learning models for automatic correctness prediction
- Real-time gesture evaluation
- Extension to more rehabilitation exercises
- Dashboard-based visualization for clinicians

---

## 👤 Author
**Abhishek M**  
ML & Visualization Work

