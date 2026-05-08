# ⏏︎ EPOCH: It's Simple - Study Management System

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red.svg)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Epoch** is a unified, AI-integrated productivity platform designed to help students and young professionals manage their daily routines effectively. By combining study tracking, expense management, and task organization into a single dashboard, Epoch eliminates the friction of juggling multiple fragmented apps.

🔗 **Repository:** [https://github.com/UtkarshTripathi-teach/Epoch_major_project](https://github.com/UtkarshTripathi-teach/Epoch_major_project)

## 🚀 Features

Epoch is divided into several core modules, all accessible from a clean, unified dashboard:

### 🎓 Study Tracker
* **Live Session Timer:** A built-in timer for focused study sessions that automatically calculates XP upon completion.
* **Manual Logging:** Log past sessions with custom durations, subjects, and confidence ratings.
* **AI Weakness Analysis:** Identifies weak topics based on historical confidence ratings and provides personalized study recommendations.

### 💸 Expense Tracker
* **Financial Dashboard:** Log daily expenses, categorize spending (Food, Transport, Utilities, etc.), and monitor your monthly budget.
* **Interactive Visualizations:** View dynamic gauge charts, pie charts, and monthly bar graphs of your spending habits.
* **ML-Based Budget Forecast:** Analyzes spending trends to predict future expenses and keep you within budget.

### ✅ Task Tracker
* **To-Do Management:** Add tasks with specific deadlines and track your completion rate.
* **Status Monitoring:** Easily toggle tasks between 'Pending' and 'Completed' with real-time progress updates.

### 🎮 Gamification System
* **XP & Leveling:** Earn Experience Points (XP) based on study duration and confidence levels. 
* **Streaks:** Maintain daily study streaks for bonus XP multipliers.
* **Achievements:** Unlock badges for reaching milestones like "Perfect Week" or logging 100+ hours of study.

### 📊 Comprehensive Reporting
* **Data Visualizations:** Interactive Plotly heatmaps, bar charts, and gauge indicators to visualize consistency and progress.
* **PDF & CSV Export:** Automatically generate and download a consolidated, beautifully formatted PDF report of your study habits, expenses, and task completion.

---

## 🛠️ Tech Stack

[cite_start]Epoch is built using a modern, lightweight data science stack[cite: 1]:
* [cite_start]**Frontend/UI:** [Streamlit](https://streamlit.io/) [cite: 1]
* [cite_start]**Data Processing:** [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/) [cite: 1]
* [cite_start]**Machine Learning:** [Scikit-learn](https://scikit-learn.org/) [cite: 1]
* [cite_start]**Data Visualization:** [Plotly](https://plotly.com/) [cite: 1]
* [cite_start]**PDF Generation:** [ReportLab](https://www.reportlab.com/) [cite: 1]

---

## 📂 Project Structure

```text
Epoch_major_project/
│
├── epochv1.py           # Main Streamlit application and UI routing
├── data_manager.py      # Core CRUD operations, authentication, and CSV file management
├── gamification.py      # Logic for XP calculation, streaks, levels, and achievements
├── pdf_exporter.py      # ReportLab layout configurations for generating consolidated PDFs
├── utils.py             # Helper functions for data formatting, metrics, and analytics
├── ml_analyzer.py       # Machine learning integrations for weakness analysis & forecasting
├── requirements.txt     # Project dependencies
└── data/                # Local directory generated at runtime to store user CSVs & Auth
