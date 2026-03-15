# 🎮 CS:GO Fuzzy Logic Player Skill Analyzer

An **AI-powered player analytics system** that evaluates FPS player skill using **Fuzzy Logic**.

This project demonstrates how Artificial Intelligence can be applied to gaming analytics by analyzing player performance metrics and estimating a player's overall skill level.

---

## 🧠 AI Concept Used

This project is based on **Fuzzy Logic**, an Artificial Intelligence technique used for reasoning with uncertain or imprecise data.

Unlike traditional systems that use fixed thresholds, fuzzy logic allows values to belong to multiple categories with different degrees of membership, making it suitable for evaluating real-world performance such as player skill.

---

## 📊 Player Metrics Analyzed

The AI system evaluates player performance using the following gameplay metrics:

| Metric | Description |
|------|-------------|
| **K/D Ratio** | Measures combat effectiveness |
| **Accuracy** | Measures aiming precision |
| **Reaction Time** | Measures player reflex speed |

These metrics are processed using **fuzzy membership functions and inference rules** to calculate a **Skill Score (0–100)**.

---

## 🏆 Skill Ranking System

The calculated skill score is mapped to a **CS-style competitive ranking system**.

| Skill Score | Rank |
|-------------|------|
| 0 – 30 | Silver |
| 30 – 50 | Gold Nova |
| 50 – 70 | Master Guardian |
| 70 – 85 | Legendary Eagle |
| 85 – 100 | Global Elite |

---

## 📈 Features

- Fuzzy Logic AI system for player evaluation
- Interactive player skill analysis
- CS-style ranking classification
- Simulated dataset of 100 players
- Skill distribution visualization
- AI heatmaps for performance analysis
- Fuzzy membership function graphs

---

## 📊 Visual Analytics

The system generates multiple visualizations including:

- Player skill distribution graphs
- AI heatmaps showing relationships between KD ratio, accuracy, and reaction time
- Fuzzy membership function visualizations

These visual tools help analyze how gameplay metrics affect overall player skill.

---

## 🧪 Example Evaluation

**Input**

KD Ratio: 2.1  
Accuracy: 68%  
Reaction Time: 180 ms  

**Output**

Skill Score: 82  
Player Rank: Legendary Eagle  

---

## 🛠️ Technologies Used

- Python
- Google Colab
- scikit-fuzzy
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 🚀 Future Improvements

Possible extensions for this project include:

- Real match data analysis
- Player performance dashboards
- Radar charts for player statistics
- Real-time gameplay analytics
- Integration with gaming APIs

---

## 🎯 Purpose

This project demonstrates how **Fuzzy Logic AI can be used for gaming analytics** to evaluate player skill in environments where performance metrics are uncertain and overlapping.

It also serves as a practical example of implementing a **Fuzzy Inference System using Python**.

