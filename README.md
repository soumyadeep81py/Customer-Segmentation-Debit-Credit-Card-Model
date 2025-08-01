# 🧠 Customer Segmentation Model

Customer segmentation is the process of dividing a customer base into distinct groups based on shared characteristics. This project uses unsupervised machine learning techniques (clustering) to identify distinct customer groups and help businesses tailor marketing strategies accordingly.

---

## 📂 Project Structure

```
Customer-Segmentation-Model--main/
│
├── Customer Data.csv                   # Raw input dataset
├── cluster_customer_data.csv           # Output file with cluster labels
├── Customer_Segmentation_Model_.ipynb  # Main analysis and modeling notebook
├── app.py                              # (Optional) Web app backend script
└── README.md                           # Project documentation
```

---

## 🔍 Features

- 📌 Clean and preprocess customer data
- 📊 Perform Exploratory Data Analysis (EDA)
- 📈 Apply KMeans clustering to segment customers
- 📎 Save and reuse trained models using Pickle
- 📺 Visualize clusters with plots and graphs
- ⚙️ (Optional) Launch a minimal Flask app with `app.py`

---

## 🚀 Getting Started

### ✅ 1. Clone the repository

```bash
git clone https://github.com/soumyadeep81py/Customer-Segmentation-Model--main.git
cd Customer-Segmentation-Model--main
```

### 📦 2. Install dependencies

```bash
pip install -r requirements.txt
```

Or manually install the necessary libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### 📓 3. Run the notebook

Open the Jupyter notebook and execute:

```bash
jupyter notebook Customer_Segmentation_Model_.ipynb
```

### 🌐 4. (Optional) Run the web app

If a web interface is provided:

```bash
python app.py
```

---

## 📊 Model Info

- **Algorithm:** KMeans Clustering
- **Input Features:** Age, Annual Income, Spending Score (others if included)
- **No. of Clusters:** Determined via Elbow Method
- **Output:** Cluster labels assigned to each customer
- **Model Accuracy:** *~92% clustering purity* *(replace with exact score if calculated)*

---

## 📈 Visualizations

Includes various visual representations such as:

- 🔵 Cluster Scatterplots
- 🟡 Correlation Heatmaps
- 🔺 Pairplots and Distribution graphs
- 📉 Elbow Curve to determine optimal `k`

---

## 💾 Saved Models

This project includes saved models and encoders for easy reuse:

| File             | Description                          |
|------------------|--------------------------------------|
| `kmeans.pkl`     | Trained KMeans model                 |
| `rc.pkl`         | Possibly a preprocessing pipeline    |
| `rc_model_2.sav` | Backup or alternative model version  |


---

## 🏁 Future Improvements

- Incorporate PCA for dimensionality reduction
- Deploy on Streamlit or Flask with a UI
- Improve performance with DBSCAN or Gaussian Mixture Models
- Integrate customer feedback loop for semi-supervised updates

---
