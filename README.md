# KPI Analysis

This repository contains a notebook developed as part of a course on **Key Performance Indicators (KPI)**.

The objective of this notebook is to explore data and evaluate performance using different KPI metrics.

## Project Objective

The goal of this assignment is to:

1. Train a sentiment classification model.
2. Evaluate its performance using **Key Performance Indicators (KPIs)**.
3. Compare different evaluation strategies including traditional ML models and Large Language Models (LLMs).



## Key Performance Indicators (KPI)

The analysis focuses on several performance indicators used to evaluate model performance:

- **Accuracy** – proportion of correct predictions among all predictions.
- **Precision** – proportion of predicted positives that are actually correct.
- **Recall** – proportion of actual positives that are correctly identified.
- **F1 Score** – harmonic mean of precision and recall, balancing both metrics.
## Evaluation Tasks

The assignment evaluates sentiment classification using four different approaches:

---

### 1. Evaluation Against a Human-Annotated Dataset

The model predictions are compared with a **human-labeled dataset**, which serves as the ground truth.  
This allows us to measure how well the model replicates human judgment.

---

### 2. Evaluation Against a State-of-the-Art Model

The performance of the trained model is compared with a **state-of-the-art baseline model**.  
This comparison helps determine whether the implemented approach performs competitively with existing solutions.

---

### 3. Zero-Shot Classification with a Large Language Model (LLM)

In this approach, a **Large Language Model (LLM)** is used without prior examples.

The model is prompted to classify each tweet directly as:

- Positive
- Negative
- Neutral

This method evaluates the capability of modern LLMs to perform classification **without task-specific training**.

---

### 4. Few-Shot Classification with an LLM

In the few-shot setting, the LLM is first provided with **example texts** labeled as:

- Positive
- Negative
- Neutral

After seeing these examples, the model is asked to classify new tweets.

This approach evaluates how providing **contextual examples** can improve LLM performance.

---

## Repository Structure

```
twitter-sentiment-analysis
│
├── KPI_2_fixed.ipynb  # Main notebook containing the analysis
├── requirements.txt   # Python dependencies
└── README.md          # Documentation
```

## Author

Theo Dupont

