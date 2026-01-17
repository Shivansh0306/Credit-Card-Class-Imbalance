# 💳 Credit Card Fraud Detection using Sampling Techniques

---

## 1. Methodology
The project follows a **simple and structured machine learning pipeline**:

<img width="2816" height="1295" alt="Methedology" src="https://github.com/user-attachments/assets/241e14aa-ca8a-4d98-a607-c4ec3d282352" />

**Important:** Sampling is applied **only on the training dataset** to prevent data leakage.

---

## 2. Project Description
This project addresses the **class imbalance problem** in credit card fraud detection by applying different **sampling techniques** and evaluating their impact on various **machine learning models**.

<img width="2816" height="1536" alt="Description" src="https://github.com/user-attachments/assets/c5dc7176-5306-4318-af5e-0b547979da2d" />


## 3. Input / Output

### Input
- Transaction feature values from the dataset  
- Imbalanced class labels  
  (`0 = Non-Fraud`, `1 = Fraud`)

### Output
- Model predictions on test data  
- Accuracy values for each **Model × Sampling** combination  

The final output is a **comparison table** showing accuracy scores for all experiments.

---

## 4. Results
- Accuracy results are stored in this type:
- <img width="898" height="272" alt="image" src="https://github.com/user-attachments/assets/47f6e8d7-ceba-4f82-ac32-dde46bc5e79a" />
This table helps identify **which sampling technique performs best for each machine learning model**.


---

## Summary
**This project demonstrates how different sampling techniques influence the performance of multiple machine learning models when trained on an imbalanced credit card fraud dataset.**
