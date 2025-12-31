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

Example filename:
