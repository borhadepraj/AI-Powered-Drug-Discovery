# AI-Powered Drug Discovery Using Deep Learning and Real-Time Data Visualization

This project explores how deep learning and AI-driven visualization can accelerate the drug discovery process by predicting molecular binding affinity and enabling interactive analysis through a web-based dashboard.


## Project Overview

Drug discovery is a complex and data-intensive process. This project implements a **deep learning-based molecular property prediction system** combined with **real-time visualization** to support faster and more accurate screening of drug candidates.


## Methodology

### Dataset Preparation
A molecular dataset is simulated with key properties:
- Molecular Weight  
- LogP (lipophilicity)  
- Binding Affinity  

### Deep Learning Model
A feed-forward neural network (regression model) is developed to predict **Binding Affinity** from molecular features:
- Input Layer: 2 features  
- Hidden Layer: ReLU activation + dropout  
- Output Layer: Predicted Binding Affinity  

### Visualization & Dashboard
- Built using **Plotly Dash**
- Real-time scatter plots of molecular properties
- Interactive filtering and trend observation for researchers


##  Novelty
- Integrates **Deep Learning** for early-stage drug screening  
- **Interactive Dashboard** for real-time data visualization  
- Simulated environment mimicking real-world drug discovery pipelines  


##  Tech Stack
- **Languages:** Python  
- **Libraries:** TensorFlow / Keras, NumPy, Pandas, Matplotlib, Plotly Dash  
- **Visualization:** Dash Web App
  

## Research Inspiration
This work is inspired by recent literature in AI-assisted drug discovery, including:
- [Traversing Chemical Space with Active Deep Learning for Low-Data Drug Discovery](https://www.nature.com/articles/s43588-024-00697-2)
- [Artificial Intelligence–Enabled Virtual Screening of Ultra-Large Chemical Libraries with Deep Docking](https://www.nature.com/articles/s41596-021-00577-0)


## Files Included
- `AI_Powered_Drug_Discovery.ipynb` – Deep learning model code  
- `report.pdf` – Research report  
- `paper_draft.pdf` – Project paper draft  

## Conclusion
This project demonstrates how combining **deep learning** with **real-time visualization** can transform the early stages of drug discovery, providing faster insights into molecular interactions and accelerating the path toward viable drug candidates.
