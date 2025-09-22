# Titanic — Data Cleaning & Preprocessing (Internship Task)

This repository contains a high-quality Jupyter Notebook designed for **data cleaning and preprocessing** on the Titanic dataset. It is structured to serve as a professional submission for internship tasks.

---

## 📂 Repository Structure

- **`titanic_preprocessing.ipynb`**  
  Complete notebook with:
  - Exploratory Data Analysis (EDA)
  - Missing value imputation
  - Feature engineering
  - Encoding categorical features
  - Scaling numeric features
  - Outlier detection and removal
  - Exporting processed data and pipeline artifacts

- **`data/`**  
  Place your Titanic dataset here as `titanic.csv`.  
  *(The notebook also uses Seaborn's built-in Titanic dataset as fallback if the file is missing.)*

- **`output/`**  
  Stores outputs:
  - `titanic_cleaned.csv` — the cleaned dataset
  - `preprocessing_pipeline.joblib` — saved preprocessing pipeline for reuse

- **`requirements.txt`**  
  Minimal Python dependencies required to run the notebook.

---

## ⚡ How to Use

1. Clone this repository:  
   ```bash
   git clone <repository_url>
2. Add the Dataset

Place the Titanic CSV file in the data/ folder as titanic.csv.
(If the file is missing, the notebook will use Seaborn's Titanic dataset for demonstration.)
3. Set Up Python Environment

Create a virtual environment and install dependencies:

python -m venv venv       # Create virtual environment
source venv/bin/activate  # Activate (Linux/Mac)
venv\Scripts\activate     # Activate (Windows)
pip install -r requirements.txt  # Install dependencies

4. Launch Jupyter Notebook
jupyter notebook titanic_preprocessing.ipynb


This will open the notebook in your browser where you can run cells step-by-step.

📊 Notebook Highlights

Exploratory Data Analysis (EDA): Understand the data distribution, visualize patterns, and identify anomalies.

Handling Missing Data: Fill missing values using median, mode, or other strategies.

Feature Engineering: Create meaningful new features like family size or title extraction.

Encoding & Scaling: Convert categorical features to numeric format and scale numeric features for modeling.

Outlier Analysis: Detect and remove extreme values using boxplots and the IQR method.

Pipeline Export: Save preprocessing steps as preprocessing_pipeline.joblib to ensure reproducibility.

📝 Notes

Notebook is fully reproducible with clear explanations for every step.

Outputs include titanic_cleaned.csv and preprocessing_pipeline.joblib in the output/ folder.

Suitable for internship submission, beginner-to-intermediate learning, or as a reference for real-world data preprocessing projects.

🔗 References

Kaggle Titanic Dataset: https://www.kaggle.com/c/titanic/data

Python Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, joblib

⚙️ Requirements
pandas
numpy
scikit-learn
matplotlib
seaborn
joblib
jupyter

📌 Author

Shivani Naroju
Guru Nanak Institutions of Technical Campus
Internship Submission: Titanic Data Cleaning & Preprocessing
