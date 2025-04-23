# Rainfall Analysis Visualization Project

This project provides detailed visual analysis of monsoon rainfall data (June to September) across various Indian subdivisions. It includes multiple visual representations like bar plots, heatmaps, scatter plots, and a donut chart to illustrate rainfall distribution and trends effectively.

## 📊 Features

- **Data Cleaning**: Handles missing values and removes erroneous rainfall data.
- **Monthly Rainfall Analysis**: Visualizes average monthly rainfall per subdivision.
- **Top Rainfall Subdivisions**: Identifies the subdivision with the highest rainfall and analyzes monthly distribution.
- **Total Rainfall Comparison**: Bar chart comparing total rainfall across all subdivisions.
- **Heatmap Visualization**: Shows detailed monthly rainfall of top two subdivisions.
- **Donut Chart**: Illustrates rainfall spread in the subdivision with the lowest rainfall.
- **Time Series Scatter Plot**: Year-wise rainfall patterns for every subdivision.

## 📁 Dataset

The script expects the input data in CSV format. Ensure your data file follows this structure:
- Columns include: `SUBDIVISION`, `YEAR`, `JUN`, `JUL`, `AUG`, `SEP`, `JUN-SEP`.
- Replace any invalid values like `-99.9` before plotting.

**Update the file path in the script to match your local CSV location.**

## 🧪 Requirements

Make sure the following Python packages are installed:

```bash
pip install pandas matplotlib seaborn numpy
🚀 How to Run
Clone the repository.

Place your rainfall dataset CSV in the project folder.

Modify the file path in CODE.py:

python
Copy
Edit
data = pd.read_csv('your_dataset.csv')  # Update path accordingly
Run the script:

bash
Copy
Edit
python CODE.py
📷 Sample Output
Average Monthly Rainfall by Subdivision (Bar Plot)

Highest Rainfall Subdivision Overview

Total Rainfall by Subdivision (Bar Chart)

Heatmap for Top Subdivisions

Donut Chart for Least Rainfall Subdivision

Yearly Scatter Plot per Subdivision

🛠️ Author
Your Name Here

Feel free to fork, modify, and contribute!
