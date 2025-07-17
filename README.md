# 🧬 COSMIC68 Cancer Mutation Analysis with Amazon Athena

This project uses Amazon Athena and PyAthena to analyze somatic mutation data from the COSMIC68 (hg19) dataset. The goal is to visualize which cancer types show up most frequently in mutation records.

## 🔍 What We Did
- Queried COSMIC68 dataset from AWS Athena
- Extracted cancer types from `cosmic_info` field
- Counted and visualized the most common cancer types using a bar chart

## 🧰 Tools Used
- Amazon Athena + AWS S3
- PyAthena (Python connector)
- Pandas + Matplotlib
- Jupyter Notebook

## 🚀 How to Run

```bash
git clone https://github.com/YOUR_USERNAME/cosmic68-cancer-analysis.git
cd cosmic68-cancer-analysis
pip install -r requirements.txt
jupyter notebook cosmic_analysis.ipynb
