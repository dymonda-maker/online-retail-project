# Customer Behavior Analysis Using Online Retail Data

👉 Start here: [main_notebook.ipynb](./main_notebook.ipynb)

🎥 Project Video: https://youtu.be/B1h-byZH-2w

## Overview
This project explores customer purchasing behavior using online retail transaction data. By applying association rule mining and sequential pattern analysis, it identifies both products that are frequently purchased together and how customer buying patterns evolve over time. The goal is to move beyond simple co-purchase relationships and uncover deeper insights into real-world customer behavior, providing a more complete understanding of how customers interact with products.
---

## Research Questions
- What products are frequently purchased together?
- How do customer purchasing patterns evolve over time?
- What additional insights can sequential pattern mining provide beyond traditional association rule mining?

---

## Dataset
This project uses the Online Retail dataset, which contains transactional data from a UK-based online retailer.

Preprocessing steps included:
- Removing canceled transactions
- Filtering out invalid quantities and prices
- Dropping missing values
- Converting transactions into a structured format for analysis

---

## How to Reproduce
This project was developed using Google Colab.

Steps to run:
1. Open `main_notebook.ipynb`
2. Upload the dataset (`Online Retail.xlsx`)
3. Run all cells from top to bottom

All required dependencies are listed in `requirements.txt`.

---

## Key Dependencies
- Python 3.12.13
- pandas 2.2.2
- numpy 2.0.2
- mlxtend 0.23.4
- matplotlib 3.10.0

(Full list available in requirements.txt)

---

## Repository Structure
project/
│
├── main_notebook.ipynb
├── requirements.txt
├── README.md
├── checkpoint_1.ipynb
├── checkpoint_2.ipynb


---

## Results Summary
The analysis revealed strong co-purchase relationships between products, particularly within similar categories. Sequential pattern mining provided deeper insights by showing how customer purchasing behavior evolves over time, highlighting patterns that traditional methods do not capture.
