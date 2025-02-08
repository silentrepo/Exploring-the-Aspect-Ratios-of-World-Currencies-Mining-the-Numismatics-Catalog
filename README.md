# 📌 Exploring the Aspect Ratios of World Currencies: Mining the Numismatics Catalog

## 📖 Overview
This project investigates the **aspect ratios of currency banknotes** across different countries and time periods. By applying **data mining, statistical analysis, and machine learning techniques**, historical trends, clustering patterns, and mathematical relationships in currency design are uncovered.

The project involves:
- 📊 **Web scraping** currency data from multiple online sources.
- 🔍 **Data preprocessing & normalization** for analytical consistency.
- 📈 **Polynomial regression & clustering** to analyze temporal and regional trends.
- ⏳ **Time-series decomposition (STL)** to separate trend, seasonal, and residual components.

---

## 📂 Project Structure

```bash
📦 world-currencies-analysis
 ┣ 📂 data               # Contains scraped and preprocessed datasets
 ┣ 📂 notebooks          # Jupyter Notebooks with step-by-step analysis
 ┣ 📂 scripts            # Python scripts for data extraction and processing
 ┣ 📂 visualizations     # Plots and graphs generated during analysis
 ┣ 📜 README.md          # Project documentation
 ┣ 📜 requirements.txt   # Dependencies needed to run the project
 ┣ 📜 LICENSE            # License information
 ┣ 📜 .gitignore         # Files and directories to ignore in Git
```
## 🛠 Installation
To set up the environment, follow these steps:
### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/world-currencies-analysis.git
cd world-currencies-analysis
```
### 2️⃣ Create a virtual environment (Optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate  # On Windows
```
### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
## 📊 Datasets
The dataset contains:

**Country Name 🇺🇳**: Identifies the issuing nation.
**Reference Number 🔢**: Unique identifier for each banknote.
**Year of Issue 📅**: Date when the banknote was introduced.
**Material Type 📜**: Specifies if the note is made of paper, polymer, or other substances.
**Dimensions 📏**: Width and height recorded in millimeters.
**Image Availability 🖼️**: Indicates if a visual reference exists.
**Web Link 🔗**: Source URL for the banknote information.
📌 The dataset is structured in CSV format to facilitate analysis.

## 🚀 Features & Methodology
### 🔍 1. Data Collection & Web Scraping
- Used **Python (Selenium, Gazpacho, BeautifulSoup)** for automated web scraping.
- Extracted **banknote attributes** from multiple sources.
- Stored the data in a **structured CSV format** for further processing.

### 📈 2. Statistical Analysis
- **Polynomial Regression**: Modeled the evolution of aspect ratios over centuries.
- **Hierarchical Clustering**: Identified distinct currency design clusters.
- **STL Decomposition**: Separated trend, seasonal, and residual components.

### 🏆 3. Machine Learning & Visualization
- Used **Scikit-learn** for regression & clustering.
- Applied **Matplotlib & Seaborn** for data visualization.
- Evaluated models using **MSE, R², Silhouette Score, and Durbin-Watson statistics**.

## 📊 Key Findings
### 📌 Temporal Trends
- **Pre-1800s**: High fluctuations in aspect ratios due to varied designs.
- **Post-1900s**: Increasing **standardization** with aspect ratios converging around **1.5 - 2.0**.
- **Golden Ratio (≈1.618)** is commonly observed in many currencies.

### 📌 Regional Differences
- **Europe & North America**: Showed more **standardized** aspect ratios.
- **Asia & Africa**: Exhibited **greater variability** in design choices.

### 📌 Material Impact
- Polymer banknotes have **slightly larger aspect ratios** than paper ones.

### 📌 Denomination Effect
- Higher currency denominations correlate with **slightly larger aspect ratios**.


## 📌 How to Run the Jupyter Notebooks
### 1️⃣ Navigate to the notebooks directory
```bash
cd notebooks
```

### 2️⃣ Run Jupyter Notebook
```bash
jupyter notebook
```

### 3️⃣ Open ```analysis.ipynb``` to explore the findings.

## 🔮 Future Work
✅ Investigate **anti-counterfeiting security features** and their impact on banknote dimensions.
✅ Expand dataset to include **cryptocurrency & digital currency dimensions**.
✅ Apply **deep learning models (CNNs)** for image-based banknote analysis.

## 📜 References
This study is supported by research from **statistical finance, machine learning, and historical currency archives**.
📌 A full list of citations is available in the paper.

## 📝 License
This project is licensed under the MIT License.

## 👩‍💻 Contributions & Acknowledgments
This research is open for contributions! If you find this project useful, consider giving it a ⭐ and submitting a pull request! 🎉












