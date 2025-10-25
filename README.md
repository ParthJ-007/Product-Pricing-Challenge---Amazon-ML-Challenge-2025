#  Product Pricing Prediction – Amazon ML Challenge 2025

##  Overview
This project was developed for the **Amazon ML Challenge 2025**.  
The objective is to predict the **price of a product** based on its **textual and visual attributes** such as title, description, and image.  

---

##  Problem Statement
In e-commerce, determining the optimal product price is crucial for business success and customer satisfaction.  
The task is to build a **machine learning model** that accurately predicts prices using multi-modal product data.

---

##  Workflow Overview
1. **Data Preprocessing**  
2. **Feature Engineering on Text Data**  
3. **Image Feature Extraction using U-Net Encoder**  
4. **Model Training using LightGBM**  
5. **Model Evaluation (SMAPE Metric)**  

---

##  Model & Performance
- **Model Used:** LightGBM Regressor  
- **Image Encoder:** U-Net (feature extraction)  
- **Final SMAPE Score:** `52.0`  


---

##  Repository Structure
```
├── model.ipynb                     # Jupyter notebook with full pipeline
├── Problem Statement and Data Description.pdf
├── README.md                       # Project documentation
├── /dataset                        # Data directory
```

---

##  Evaluation Metric
**Symmetric Mean Absolute Percentage Error (SMAPE):**

SMAPE = (1/n) * Σ |predicted_price - actual_price| / ((|actual_price| + |predicted_price|)/2)
Lower SMAPE → Better performance.

---

##  Tech Stack
- Python  
- Pandas, NumPy, Scikit-learn  
- LightGBM  
- PyTorch   
- Jupyter Notebook  

---
