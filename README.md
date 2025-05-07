# Udemy-Unlocked-Insights
# 📘 Udemy-Course-Explorer
![Udemy](https://img.shields.io/badge/Platform-Udemy-blueviolet)
![Python](https://img.shields.io/badge/Python-3.10+-green)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Last Update](https://img.shields.io/badge/Last_Update-May_2025-orange)

## 🎓 Welcome to the **Udemy Course Explorer** Project!

This repository contains an end-to-end data analysis project focused on Udemy’s online courses. The project uses Python and Plotly to uncover key patterns in course pricing, ratings, popularity, and category trends to help learners and educators make informed decisions.

---

## 📑 Table of Contents

- [📌 Project Overview](#project-overview)
- [🧾 Dataset Information](#dataset-information)
- [📊 Key Highlights](#key-highlights)
- [📂 Visualizations](#visualizations)
- [🛠️ Technologies Used](#technologies-used)
- [🚀 Installation and Usage](#installation-and-usage)
- [🧱 Project Structure](#project-structure)
- [🔮 Future Work](#future-work)
- [🤝 Contributions](#contributions)
- [📄 License](#license)

---

## 📌 Project Overview

The objective of this project is to derive actionable insights from Udemy course listings by analyzing various features such as:

- Course pricing trends across categories
- Relationship between course ratings and student enrollment
- Duration and content length impact on popularity
- Paid vs Free course performance
- Top instructors and subject domains

---

## 🧾 Dataset Information

- **Platform**: Udemy
- **Total Records**: ~3,000+ courses
- **Features**:
  - `course_title`
  - `category`, `subcategory`
  - `course_type` (Free/Paid)
  - `price`
  - `num_subscribers`
  - `num_reviews`
  - `content_duration`
  - `published_timestamp`

### 📥 Source
The dataset was downloaded from [Kaggle](https://www.kaggle.com/) and represents a snapshot of public Udemy course data.

---

## 📊 Key Highlights

- 💰 **Free vs Paid**: Paid courses dominate with higher enrollments and better reviews, but free courses attract beginners.
- 🧠 **Top Categories**: Web Development, Business, and IT & Software lead in both volume and popularity.
- 📈 **Course Duration Insight**: Sweet spot for duration lies between 2–6 hours.
- 🌟 **High Ratings ≠ High Subscribers**: Several high-rated courses have relatively fewer enrollments.
- 🧑‍🏫 **Top Instructors**: A few instructors consistently produce high-enrollment content.

---

## 📂 Visualizations

All visualizations are interactive and built using **Plotly** for better user engagement:

- 📊 Bar Plot: Course count per category
- 💰 Box Plot: Price distribution by subcategory
- 📈 Scatter Plot: Subscribers vs Ratings
- 🕒 Horizontal Bar: Duration comparison
- 🔥 Pie Chart: Free vs Paid course distribution
- 🧮 Count Plot: Courses by content length range

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **Pandas** for data manipulation
- **Plotly Express** for visualization
- **Jupyter Notebook** for analysis presentation
- **GitHub** for version control and sharing

---

## 🚀 Installation and Usage

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Udemy-Course-Explorer.git
cd Udemy-Course-Explorer

