# B2B Brand Equity Analysis using ML, NLP & Monte Carlo Simulation

> SURGE'25 Research Project — Indian Institute of Technology Kanpur  
> **Mentor:** Prof. R. N. Sengupta  
> **Author:** Ayush Raj  
> **Domain:** Data Science | Machine Learning | NLP | Statistical Analysis | Marketing Analytics

---

## 📌 Overview

This project develops a data-driven framework to analyze and quantify **B2B Brand Equity** using statistical analysis, machine learning, NLP-based semantic analysis, and Monte Carlo simulation.

The study examines five major B2B firms:

- Salesforce
- Adobe
- Intuit
- Oracle
- SAP

B2B brand equity is modeled using five dimensions:

- **Brand Awareness**
- **Brand Reputation**
- **Trust**
- **Customer Loyalty**
- **Perceived Quality**

The project combines multiple analytical approaches to understand relationships between these dimensions, classify firms based on brand-equity levels, analyze digital brand prominence, and quantify uncertainty in the estimated Brand Equity Score.

The research was conducted as part of the **SURGE'25 program at IIT Kanpur**.

---

## 🎯 Objectives

The major objectives of the project were:

1. Identify important dimensions associated with B2B brand equity.
2. Analyze relationships between awareness, reputation, trust, loyalty and quality.
3. Develop an exploratory ML model for classifying firms into high and non-high brand-equity categories.
4. Quantify digital brand prominence using a **Semantic Brand Score (SBS)**.
5. Analyze digital marketing effectiveness using Marketing ROI concepts.
6. Model uncertainty in brand perception using **Monte Carlo simulation**.
7. Develop a quantitative framework for analyzing brand equity under uncertainty.

---

# 🧠 Project Architecture

```text
                     B2B Brand Equity
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
       Structured       Digital Text    Marketing Data
          Data              Data             │
             │              │                │
             ▼              ▼                ▼
      Correlation       NLP Pipeline       MROI
        Analysis             │
             │               ▼
             │        Semantic Network
             │               │
             │               ▼
             │        Semantic Brand
             │            Score
             │
             ▼
      Logistic Regression
             │
             ▼
      High Equity Probability
             │
             └──────────────┐
                            ▼
                    Monte Carlo Simulation
                            │
                            ▼
                   Brand Equity Distribution
                            │
                            ▼
                  Risk & Uncertainty Analysis
