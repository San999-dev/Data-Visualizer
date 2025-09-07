📊 Data Visualizer
🔹 Overview

This project is a Python-based data visualization tool.
It loads a dataset, preprocesses it, and generates visual insights such as histograms, correlation heatmaps, and category counts.
All plots are saved automatically into a plots/ folder.

🔹 How to Run

Clone this repository:

git clone https://github.com/your-username/data-visualizer.git
cd data-visualizer


Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn


Place your dataset in the project folder and rename it as:

data_visualizer_dataset.csv


Run the script:

python data_visualizer.py

🔹 Output

After running, a new folder plots/ will be created containing:

histograms.png – Distribution of numeric features

correlation_heatmap.png – Heatmap of feature correlations

category_counts.png – Count distribution of categories (if dataset has a Category column)


🔹 Future Improvements

Add support for interactive plots (Plotly, Streamlit)

Export reports as PDF/Excel

Auto-detect categorical features
