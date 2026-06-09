# AI-Powered Smart Business Intelligence System



---

## What We Did

### 1. Dataset
- Created a customer churn dataset with 500 records and 14 features
- Features include Age, Gender, Tenure, Monthly Charges, Contract Type, Satisfaction Score, Number of Complaints, and more
- Churn rate was 28.2%

### 2. Data Preprocessing
- Handled missing values in Age, SatisfactionScore, NumComplaints, and TotalCharges using median and mode
- Applied Label Encoding to Gender, ContractType, and PaymentMethod
- Scaled all features using StandardScaler
- Split data into 80% training and 20% test sets (400 train, 100 test)

### 3. Classification – Random Forest
- Trained a Random Forest Classifier with 100 trees
- Achieved **68% accuracy**
- Generated confusion matrix and feature importance chart
- Top predictors: Tenure, TotalCharges, MonthlyCharges, SatisfactionScore

### 4. Clustering – K-Means
- Used Elbow Method to find optimal k = 4
- Identified 4 customer segments:
  - Segment 1 – Loyal High-Value customers (15% churn)
  - Segment 2 – At-Risk Veterans (30% churn)
  - Segment 3 – Low Satisfaction customers (42% churn)
  - Segment 4 – Multi-Product Users (27% churn)

### 5. Deep Learning – ANN
- Built an Artificial Neural Network with 3 hidden layers (64 → 32 → 16 neurons)
- Used BatchNormalization, Dropout, and EarlyStopping
- Achieved **78% accuracy** — better than Random Forest
- Plotted accuracy and loss curves across epochs

### 6. Generative AI Prompts
- Wrote 3 smart prompts for churn strategy, segment targeting, and model improvement
- Generated 5 business recommendations based on model results

---

## Files
- `AI_Business_Intelligence_RUDHRESH.ipynb` — full code notebook (run on Google Colab)
- `customer_churn_cleaned.csv` — cleaned dataset
- `AI_BI_System_RUDHRESH.pptx` — 5-slide presentation

---

## Results

| Task | Result |
|------|--------|
| Random Forest Accuracy | 68% |
| ANN Accuracy | 78% |
| Customer Segments | 4 |
| Churn Rate | 28.2% |
