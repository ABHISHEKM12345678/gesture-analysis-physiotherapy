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
![skeleton](https://github.com/user-attachments/assets/5ed23b13-6df2-4dab-8e41-182d0d93d8cd)

---

## 🤖 Gesture Analysis
- Supports **9 gesture classes (GestureLabel 0–8)**
- For each gesture:
  - Multiple samples are visualized
  - Correctness is evaluated using metadata
- Helps identify **common incorrect movement patterns**
- Useful for **qualitative assessment** rather than clinical diagnosis

---
![gesture_0_correct_vs_incorrect](https://github.com/user-attachments/assets/acaedb0d-9718-439a-9aa8-c45694c30baf)
![gesture_1_correct_vs_incorrect](https://github.com/user-attachments/assets/e03a7ace-963d-48f5-a37b-3637ab66dd25)
![gesture_2_correct_vs_incorrect](https://github.com/user-attachments/assets/02a2a627-c0e1-4781-a602-022dca1a85bf)
![gesture_3_correct_vs_incorrect](https://github.com/user-attachments/assets/2134b956-a1d6-4d4c-9433-b1b734f702dd)
![gesture_4_correct_vs_incorrect](https://github.com/user-attachments/assets/6389adce-3bbc-4bef-a4c8-a07cae36048a) 
![gesture_5_correct_vs_incorrect](https://github.com/user-attachments/assets/2941f266-162c-4c4d-9e83-512eecf66546)
![gesture_6_correct_vs_incorrect](https://github.com/user-attachments/assets/40bc8966-c6b4-44f1-8711-a08826da798b)
![gesture_7_correct_vs_incorrect](https://github.com/user-attachments/assets/e1dcd7f2-4467-45ca-96ec-b6f01d1c7ee0)
![gesture_8_correct_vs_incorrect](https://github.com/user-attachments/assets/4777b7f0-42a8-4118-bab4-3688a21b468e)




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

