# 🌤️ Weather Data Analysis using Python & Pandas

A data analysis project built in Python that explores a real-world Weather dataset. This project covers essential data analysis operations — from exploratory data analysis (EDA) to filtering, grouping, and statistical calculations — using the Pandas library.

---

## 📌 Project Overview

This project applies fundamental data analysis techniques to a Weather dataset, answering 15 structured analytical questions. It serves as a strong foundation for anyone learning data wrangling, EDA, and querying with Pandas.

---

## 🗂️ Dataset

- **File:** `Weather_Data.csv`
- **Domain:** Meteorology / Climate
- **Key Columns:** `Weather`, `Wind Speed_km/h`, `Visibility_km`, `Press_kPa`, `Rel Hum_%`

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation & analysis |
| Google Colab | Development environment |

---

## 📋 Questions & Tasks Covered

| # | Question |
|---|----------|
| Q1 | Find all unique **Wind Speed** values in the data |
| Q2 | Find the number of times **Weather is exactly "Clear"** |
| Q3 | Find the number of times **Wind Speed was exactly 4 km/h** |
| Q4 | Find all **Null Values** in the dataset |
| Q5 | **Rename** the column `Weather` to `Weather Condition` |
| Q6 | What is the **mean Visibility**? |
| Q7 | What is the **standard deviation of Pressure**? |
| Q8 | What is the **variance of Relative Humidity**? |
| Q9 | Find all instances when **Snow** was recorded |
| Q10 | Find instances when **Wind Speed > 24** and **Visibility = 25** |
| Q11 | Mean value of each column against each **Weather Condition** |
| Q12 | Min & Max value of each column against each **Weather Condition** |
| Q13 | Show all records where **Weather Condition is Fog** |
| Q14 | Instances when **Weather is Clear** OR **Visibility > 40** |
| Q15 | Instances when (**Weather is Clear** AND **Humidity > 50**) OR **Visibility > 40** |

---

## 🔍 Key Pandas Concepts Used

- **EDA:** `.head()`, `.shape`, `.info()`, `.dtypes`, `.describe()`
- **Unique & Count:** `.unique()`, `.nunique()`, `.value_counts()`
- **Null Handling:** `.isnull()`, `.notnull()`
- **Filtering:** Boolean indexing with `==`, `>`, `&`, `|`
- **String Matching:** `.str.contains()`
- **GroupBy:** `.groupby().get_group()`, `.groupby().mean()`, `.groupby().min()`, `.groupby().max()`
- **Statistics:** `.mean()`, `.std()`, `.var()`
- **Renaming:** `.rename(columns={})`

---

## 🚀 Getting Started

### Option 1: Run on Google Colab *(Recommended)*
1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/)
2. Upload `Weather_Data.csv` when prompted
3. Run all cells sequentially

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Install dependencies
pip install pandas

# Launch Jupyter Notebook
jupyter notebook Python_Data_Analysis_Project.ipynb
```

> **Note:** If running locally, replace the Google Colab file upload block with:
> ```python
> data = pd.read_csv("Weather_Data.csv")
> ```

---

## 📁 Repository Structure

```
📦 your-repo-name
 ┣ 📓 Python_Data_Analysis_Project.ipynb   # Main notebook
 ┣ 📄 Weather_Data.csv                      # Dataset
 ┗ 📄 README.md                             # Project documentation
```

---

## 💡 Key Learnings

- Performing EDA to quickly understand the structure and content of a dataset
- Using multiple approaches (filtering, `value_counts()`, `groupby()`) to answer the same question
- Applying compound conditions with AND (`&`) and OR (`|`) operators
- Using `str.contains()` for flexible text-based filtering
- Computing descriptive statistics (mean, std, variance) on specific columns
- Grouping data to compare statistics across categories

---

## 🙌 Acknowledgements

This project was completed as part of a Python Data Analysis learning exercise using a publicly available Weather dataset.

---

## 📬 Contact

Feel free to connect or raise an issue if you have suggestions or questions!
