# 📊 EDA Analysis on E-Books (Project Gutenberg)

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of e-books collected from **Project Gutenberg**, an online digital library.  
The analysis helps understand **book popularity, author contributions, language distribution, and user engagement trends** based on download activity.

---

## 🌐 Data Source & Web Scraping
**Website:** https://www.gutenberg.org/

Web scraping was used to collect book-related data because:
- Data is not directly available in a structured format
- Automation saves time and improves accuracy
- Useful for large-scale data analysis

**Libraries used:**
- `requests`
- `BeautifulSoup`
- `pandas`

---

## 🧠 Business Problem
How can virtual libraries or online publishing platforms:
- Identify **most popular books and authors**?
- Understand **preferred reading formats** (EPUB, Kindle, Text)?
- Analyze how **file size and availability** influence downloads?

---

## 🎯 Objectives
- Collect and clean e-book data from Project Gutenberg
- Identify popular books, authors, and languages
- Analyze download behavior and user preferences
- Provide insights for **digital publishers and e-libraries**
- Improve **user experience and content strategy**

---

## 🧹 Data Cleaning
- Removed null and duplicate values
- Reformatted columns
- Standardized categorical values
- Created a clean and structured dataframe for analysis

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Histograms for numeric columns (Book ID, Downloads)
- Count plots for categorical columns (Release Years, Languages)

**Key Observations:**
- Book IDs and downloads are right-skewed
- Majority of books are clustered within a specific ID range
- Release years show an uneven distribution

---

### 🔹 Bivariate Analysis
- Author vs Language (Stacked Bar Charts)
- File size vs Downloads
- Categorical vs categorical comparisons

**Insights:**
- Some authors dominate specific languages
- Authors with multi-colored bars publish in multiple languages
- Downloads are largely independent of file size

---

### 🔹 Multivariate Analysis
- Correlation heatmaps
- Cluster maps (Title vs Author)

**Key Findings:**
- File sizes across formats are highly correlated (0.96 – 0.99)
- Downloads show weak correlation with file size
- English language dominates the dataset
- Similar author-language patterns form clear clusters

---

## 📈 Key Insights
- 📖 **Most Popular Book:** *Frankenstein; Or, The Modern Prometheus*
- ✍️ **Top Authors:** Charles Dickens, Mark Twain, Plato, Nietzsche
- 🌍 **Dominant Language:** English
- 📉 Downloads are **not influenced** by file size
- 🧩 Many books are listed under “Unknown” authors

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Techniques:** Web Scraping, Data Cleaning, EDA  

---

## 📁 Project Structure
```

├── data/
│   └── cleaned_dataset.csv
├── notebooks/
│   └── eda_analysis.ipynb
├── visuals/
│   └── plots_and_charts
└── README.md

```

---

## ✅ Conclusion
This EDA project provides valuable insights into:
- Reader preferences
- Content popularity
- Publishing trends

These insights can help **digital libraries and publishers** optimize their collections and improve user engagement.

---

## 🙏 Acknowledgement
Thanks to **Project Gutenberg** for providing open-access e-book data.

---

## 👩‍💻 Author
**Name:** Tripura Rajesh Satonkar  
**Education:** Bachelor of Computer Applications (BCA), Final Year  
**College:** Dayanand College of Commerce, Latur  

🔗 **LinkedIn:** https://www.linkedin.com/in/tripura-satonkar-3849b1352  
🔗 **GitHub:** https://github.com/TripuraSatonkar  

---


## 📬 Contact
Feel free to connect with me on LinkedIn or explore my GitHub for more projects!

**— Tripura Rajesh Satonkar**
```

---
