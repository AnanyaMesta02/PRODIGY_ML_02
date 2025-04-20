# PRODIGY_ML_02
"A machine learning model using K-Means clustering to segment retail store customers based on their income and spending behavior.

# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers of a retail store based on their **Annual Income** and **Spending Score**. The goal is to identify different types of customers (e.g., high spenders, low spenders) to improve marketing strategies and customer experience.

---

## 📊 Features

- K-Means clustering implementation using `scikit-learn`
- Clusters customers based on behavior patterns
- Visualizations using `matplotlib` and `seaborn`
- Customizable for real-world customer datasets

---

## 🧠 Algorithms Used

- **K-Means Clustering**  
  Groups similar data points into `K` distinct clusters using distance-based centroids.

---

## 📁 Project Structure

## 📁 Project Structure

customer-segmentation/ │ ├── customers.csv # Sample customer data (optional) ├── customer_segmentation.py # Main Python script └── README.md # Project documentation

---

## ⚙️ Requirements

Make sure you have Python 3 installed. Then install the required libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn
🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
(Optional) Place a file named customers.csv in the same directory. If not available, the script will generate dummy data.

Run the script:

bash
Copy
Edit
python customer_segmentation.py
📸 Output
📌 A color-coded scatter plot showing customer clusters

✨ Cluster centroids marked with an "X"

📈 Optional heatmaps or pair plots for deeper insight

📝 Sample Data Format (customers.csv)
csv
Copy
Edit
CustomerID,Annual Income (k$),Spending Score (1-100)
1,15,39
2,16,81
3,17,6
...
📬 Contact
For suggestions or contributions, feel free to open an issue or a pull request!
