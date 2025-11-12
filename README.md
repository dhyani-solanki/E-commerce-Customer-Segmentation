🛍️ Customer Segmentation using K-Means Clustering
📊 Project Overview

This project is a Flask-based web application for Customer Segmentation and Cluster Analysis. It allows users to upload a CSV file containing customer data, automatically perform clustering using K-Means, and visualize meaningful customer groups such as Budget Shoppers, High Spenders, Occasional Buyers, and Loyal Customers.

The app also provides interactive visualizations like the Elbow Curve, PCA plots (2D & 3D), Pairplots, and Cluster Distribution charts, helping businesses better understand their customers and make data-driven marketing decisions.

🚀 Key Features

✅ Upload CSV Files — Upload your customer dataset directly through the web interface.
✅ Automated Preprocessing — Automatically detects numeric columns and scales them for clustering.
✅ K-Means Clustering — Groups customers into four segments using K-Means and labels them meaningfully.
✅ Performance Metric — Displays the Silhouette Score to indicate clustering quality.
✅ Visual Insights:
📈 Elbow Method to determine optimal cluster count
🔵 Pairplot to visualize relationships between features
🎨 2D & 3D PCA Visualization for reduced-dimensional insight
🥧 Pie Chart & Bar Chart for cluster distribution
✅ Downloadable Output — Saves a labeled CSV file (clustered_customers_labeled.csv) with assigned customer segments.

🧠 Tech Stack
Component	Technology
Frontend	HTML, CSS (Bootstrap templates)
Backend	Python (Flask)
Data Analysis	Pandas, NumPy, Scikit-learn
Visualization	Matplotlib, Seaborn
Clustering Algorithm	K-Means, PCA
File Handling	CSV Uploads stored in /static/uploads/

⚙️ How It Works
Upload your dataset (.csv file) via the web interface.
The app preprocesses your data — selecting only numeric features and scaling them.
Performs K-Means clustering with 4 clusters.
Calculates the Silhouette Score for performance evaluation.
Generates and saves visualizations for analysis:
Elbow curve
Pairplot
PCA (2D & 3D) projections
Cluster distribution (Pie & Bar)
Displays the top 10 clustered records and allows users to view all results.

🧩 Folder Structure
📦 CustomerSegmentationApp
├── app.py
├── templates/
│   ├── index.html
│   └── result.html
├── static/
│   └── uploads/
│       ├── elbow.png
│       ├── pairplot.png
│       ├── pca_2d.png
│       ├── pca_3d.png
│       ├── cluster_distribution_pie.png
│       ├── cluster_distribution_bar.png
│       └── clustered_customers_labeled.csv
├── requirements.txt
└── README.md


🧪 Example Use Cases :
🎯 Marketing segmentation and personalization
🛒 Retail analytics
📊 Customer lifetime value analysis
💬 Targeted advertising strategies

If you’d like to enhance the project, submit a pull request or open an issue for discussion.
