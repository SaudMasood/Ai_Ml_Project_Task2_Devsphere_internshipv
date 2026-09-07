# 🤖 AI/ML Project Task 2 — DevSphere Internship

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=DevSphere+AI%2FML+Internship;Week+2+Task;Search+Algorithms+%7C+Data+Visualization;Python+%7C+Pandas+%7C+Matplotlib" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=2" width="90%">
</p>

<p align="center">
  <b>🚀 Artificial Intelligence & Machine Learning</b><br>
  <b>📅 Week 02 • September 2026</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/DevSphere-Internship-36BCF7?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-Search%20Algorithms-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ML-Data%20Visualization-FF6B6B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

---

## 👨‍💻 Intern Information

| Information | Details |
|---|---|
| 👤 **Name** | **Saud Masood** |
| 🎯 **Domain** | **Artificial Intelligence & Machine Learning** |
| 🏢 **Internship** | **DevSphere Internship Program** |
| 📚 **Task** | **Week 02 — AI & ML** |
| 📅 **Report Date** | **5 September 2026** |
| ⏰ **Submission Deadline** | **14 September 2026** |

---

# 📌 Week 2 Overview

This repository contains my **Week 2 AI/ML internship tasks** completed as part of the **DevSphere Internship Program**.

This week's work focuses on two practical areas:

```text
                    WEEK 02
                       │
            ┌──────────┴──────────┐
            │                     │
            ▼                     ▼
       🤖 ARTIFICIAL         📊 MACHINE
       INTELLIGENCE           LEARNING
            │                     │
            ▼                     ▼
     Search Algorithms      Data Visualization
            │                     │
       ┌────┴────┐          ┌─────┼─────┐
       │         │          │     │     │
    Linear    Binary      Bar   Line   Pie
    Search    Search      Chart Chart Chart
````

---

# 🤖 Task 1 — Artificial Intelligence

## 📚 Topic

**Search Algorithms**

## 🎯 Task Requirement

Implement search algorithms and demonstrate their working with examples.

### Requirements

* 🔎 Linear Search
* ⚡ Binary Search
* 🧪 Demonstrate both algorithms with an example
* 📊 Compare their basic performance

### 📤 Output

A Python program that implements both search algorithms and displays their results.

---

## 🔎 Linear Search

Linear Search checks the elements of a list one by one from the beginning until the target value is found.

### Example

```text
Data:
[10, 20, 30, 40, 50, 60, 70, 80, 90, 100]

Target:
70
```

The algorithm checks the values sequentially until it reaches `70`.

```text
10 → 20 → 30 → 40 → 50 → 60 → 70
                              ↑
                           Found
```

### ⏱️ Complexity

```text
Time Complexity: O(n)
```

---

## ⚡ Binary Search

Binary Search works on a **sorted list**.

Instead of checking every element, it checks the middle element and repeatedly reduces the search range.

```text
[10, 20, 30, 40, 50, 60, 70, 80, 90, 100]
                    ↓
                Check Middle
                    ↓
             Reduce Search Area
                    ↓
                  Find 70
```

### ⏱️ Complexity

```text
Time Complexity: O(log n)
```

---

## 📊 AI Performance Comparison

| Algorithm        | Approach                        | Time Complexity |
| ---------------- | ------------------------------- | --------------- |
| 🔎 Linear Search | Checks elements one by one      | **O(n)**        |
| ⚡ Binary Search  | Divides the sorted search range | **O(log n)**    |

For my Google Colab test, both algorithms successfully found the target value `70` at index `6`.

The measured execution times were very close because the example dataset is small.

---

# 📊 Task 2 — Machine Learning

## 📚 Topic

**Data Visualization**

## 🎯 Task Requirement

Visualize a dataset and present useful insights from the data.

### Requirements

* 🐍 Use Python
* 📊 Use Matplotlib / Seaborn
* 📈 Create a bar chart
* 📉 Create a line chart
* 🥧 Create a pie chart
* 💡 Show insights from the data
* 🏷️ Keep charts clean and labeled

### 📤 Output

Graphs with explanations and data insights.

---

# 📁 Dataset

The visualization task uses:

```text
cleaned_students.csv
```

The dataset contains student information including:

```text
Name
Age
Gender
Math
English
Science
```

The cleaned dataset is used for calculating subject averages and creating visualizations.

---

# 📊 Subject Performance

The program calculates the average score for each subject.

| Subject     | Average Score |
| ----------- | ------------: |
| Mathematics |     **81.75** |
| English     |     **82.67** |
| Science     |     **84.80** |

### 🏆 Highest Average

**Science — 84.80**

### 📉 Lowest Average

**Math — 81.75**

### 📊 Overall Average

**83.07**

---

# 📊 Visualization 1 — Bar Chart

The bar chart compares the average scores of the three subjects.

```text
Math       █████████████████
English    █████████████████
Science    ██████████████████
```

### 💡 Insight

Science has the highest average score, while Math has the lowest average score among the three subjects.

---

# 📈 Visualization 2 — Line Chart

The line chart shows the change in average scores across the three subjects.

```text
Math
  ●
   \
    ● English
       \
        ● Science
```

### 💡 Insight

The average score increases from Math to English and reaches its highest point in Science.

---

# 🥧 Visualization 3 — Pie Chart

The pie chart represents the gender distribution of the students.

```text
Male       → 6 students → 60%
Female     → 4 students → 40%
```

### 💡 Insight

The dataset contains **6 male students and 4 female students**.

---

# 🔍 Data Insights

The analysis produced the following observations:

### 🥇 Subject Performance

**Science** has the highest average score at **84.80**.

### 📉 Lowest Subject Average

**Math** has the lowest average score at **81.75**.

### 📊 Overall Performance

The overall average across the three subjects is **83.07**.

### 👥 Gender Distribution

There are:

* **6 Male students — 60%**
* **4 Female students — 40%**

---

# 🛠️ Technologies Used

<p align="center">

<img src="https://skillicons.dev/icons?i=python" />

</p>

| Technology          | Purpose                                  |
| ------------------- | ---------------------------------------- |
| 🐍 **Python**       | Programming and algorithm implementation |
| 🐼 **Pandas**       | Dataset loading and analysis             |
| 📊 **Matplotlib**   | Data visualization                       |
| 📄 **CSV**          | Dataset storage                          |
| ☁️ **Google Colab** | Development and execution environment    |

---

# 📂 Repository Structure

```text
AI_ML_Project_Task2_DevSphere_Internship/
│
├── 🐍 ai_ml_week2.py
│
├── 📄 Week_2_AI_ML_Report.docx
│
├── 📊 students.csv
│
└── 🧹 cleaned_students.csv
```

---

# ▶️ How It Works

## Step 1 — AI Search Algorithms

The Python program:

```text
Start
  ↓
Create sorted list
  ↓
Select target value
  ↓
Run Linear Search
  ↓
Run Binary Search
  ↓
Compare results
  ↓
Display performance
```

---

## Step 2 — ML Data Visualization

The Python program:

```text
cleaned_students.csv
        ↓
Load with Pandas
        ↓
Calculate subject averages
        ↓
Analyze gender distribution
        ↓
Create Bar Chart
        ↓
Create Line Chart
        ↓
Create Pie Chart
        ↓
Display insights
```

---

# 💻 Execution Environment

The tasks were implemented and tested using:

```text
Google Colab
Python
Pandas
Matplotlib
```

The repository contains the code and supporting dataset used for the Week 2 tasks.

---

# ✅ Task Completion

| Week 2 Requirement         | Status      |
| -------------------------- | ----------- |
| 🔎 Linear Search           | ✅ Completed |
| ⚡ Binary Search            | ✅ Completed |
| 🧪 Search Example          | ✅ Completed |
| 📊 Performance Comparison  | ✅ Completed |
| 📊 Bar Chart               | ✅ Completed |
| 📈 Line Chart              | ✅ Completed |
| 🥧 Pie Chart               | ✅ Completed |
| 💡 Data Insights           | ✅ Completed |
| 🏷️ Clean & Labeled Charts | ✅ Completed |
| 💻 Python Implementation   | ✅ Completed |
| 📸 Screenshots & Outputs   | ✅ Included  |
| 📄 Week 2 Report           | ✅ Included  |

---

# 🎓 Learning Outcomes

Through this week's tasks, I practiced:

* Python programming
* Search algorithms
* Linear Search
* Binary Search
* Algorithm complexity
* Basic performance comparison
* Pandas data analysis
* Matplotlib visualization
* Bar charts
* Line charts
* Pie charts
* Dataset interpretation
* Presenting data-driven insights

---

# 🚀 Week 2 Completed

<p align="center">

### 🤖 AI + 📊 ML + 🐍 Python

**Search Algorithms + Data Visualization**

<br>

**🎉 Week 2 AI/ML Internship Tasks Successfully Completed!**

</p>

---

## 👨‍💻 Author

<p align="center">

**Saud Masood**

<br>

AI/ML Intern
**DevSphere Internship Program**

Artificial Intelligence & Machine Learning

<br>

📅 **Week 02 — 5 September 2026**

</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=36BCF7&height=120&section=footer" />
</p>
