# Shopping Hard or Hardly Shopping: Customer Segmentation Using Clickstream Data

## 📌 Overview
This project uses machine learning to segment online shopping customers based on their clickstream and purchasing behavior. It uses Gower Distance and PAM-based K-Medoids clustering to identify different customer segments and analyze their revenue.

## 🎯 Features
- Upload and analyze clickstream dataset
- Data preprocessing and normalization
- Gower Distance Matrix
- PAM / K-Medoids clustering
- Silhouette Score analysis
- Cluster-based revenue analysis
- Customer segmentation visualization

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Scikit-learn-extra
- Matplotlib
- Gower Distance
- K-Medoids

## 📊 Dataset
Clickstream Data for Online Shopping – UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/553/clickstream+data+for+online+shopping

## ▶️ How to Run

Install the required packages:

```bash
pip install -r requirements.txt
Run the project:
python ClickStream.py

Or double-click run.bat on Windows.
📈 Results
The project evaluates different numbers of clusters using Silhouette Score. Based on the results, 6 clusters achieved the best score. The project also visualizes the customer segments and analyzes revenue across clusters.
🌟 Extension
The project extends the existing approach by adding a visual customer segmentation graph, making it easier to understand the distribution of customers across different clusters.
