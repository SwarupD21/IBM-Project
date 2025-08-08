# Development of a Personalized Learning Pathway Recommender

This project focuses on the **development of a personalized learning pathway recommender system** using AI/ML techniques. The aim is to assist learners by suggesting the most suitable sequence of topics or courses based on their background, preferences, and progress. The model is developed and tested using **Google Colab** with a suitable dataset.

The solution is built using a **custom AI agent**, enhanced with Google’s **Gemini API**, and implemented in **Google Colab** for seamless experimentation and deployment.
---

## 🚀 Overview

In the era of e-learning, one-size-fits-all content delivery fails to meet the diverse needs of learners. This recommender system is designed to offer **customized learning paths** using machine learning models trained on user interaction data, performance metrics, and learning goals.

This project:
- Uses AI/ML to analyze learner profiles and course metadata.
- Recommends tailored learning sequences.
- Is implemented using Python and open-source libraries in **Google Colab**.

---

## 📁 Dataset

The dataset contains anonymized learner data, course content, engagement metrics, and performance scores.

---

## 🌐 Key Features

- ✅ AI Agent designed to recommend **customized learning paths**
- ✅ Uses **Gemini API key** for advanced language understanding and recommendation
- ✅ Designed to scale for different learners and domains
- ✅ Developed and tested in **Google Colab**

---

## 🔐 Gemini API Integration

To use the Gemini AI Agent:

1. Generate your Gemini API key from [https://makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey).
2. In the Colab notebook, add the API key like this:

```python
import google.generativeai as genai

genai.configure(api_key="GOOGLE_API_KEY")

---
