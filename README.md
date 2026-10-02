# 📚 Books to Scrape – Price & Rating Analysis

## 📌 Project Overview

This project focuses on collecting, cleaning and analyzing book data from the **Books to Scrape** website.

I collected **1,000 book records from 50 pages** using Python, Requests and BeautifulSoup. The collected data was cleaned and analyzed to understand book prices, ratings and title length.

The final analysis was presented through an interactive **Power BI dashboard**.

---

## 🎯 Project Objectives

- Collect book data from the Books to Scrape website
- Clean and prepare the scraped data
- Analyze book prices and ratings
- Analyze title length
- Create price categories
- Study the relationship between price and rating
- Build an interactive Power BI dashboard
- Generate practical business insights

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Requests
- BeautifulSoup
- Google Colab
- Power BI

---

## 🔄 Project Workflow

1. Web Scraping
2. Data Collection
3. Data Cleaning
4. Feature Creation
5. Exploratory Data Analysis
6. Price Analysis
7. Rating Analysis
8. Correlation Analysis
9. Power BI Dashboard

---

## 🕷️ Web Scraping

Data was collected from the **Books to Scrape** website using:

- Python
- Requests
- BeautifulSoup

### Data Collected

The original dataset contained:

- Book Title
- Price
- Rating

A total of **1,000 books were collected from 50 pages**.

---

## 🧹 Data Cleaning & Preparation

The scraped data was prepared for analysis.

### Cleaning Steps

- Converted price into numeric format
- Converted rating from words into numbers from 1 to 5
- Checked missing values
- Checked duplicate records

### Result

- Rows: **1,000**
- Original columns: **3**
- Final columns: **5**
- Missing values: **None**
- Duplicate records: **None**

### New Features Created

- `title_length`
- `price_category`

Price categories were created as:

- Low
- Medium
- High

---

## 📊 Key Analysis & Findings

### Average Book Price

The average book price was approximately **£35.07**.

### Average Rating

The average rating was approximately **2.92 stars**.

### Average Title Length

The average title length was approximately **39.12 characters**.

### Price Range

Book prices ranged from approximately **£10 to £59.99**.

---

## ⭐ Rating Analysis

- 1-star books: **226**
- 4-star books: **179**
- Average rating: **2.92 stars**

The 1-star rating group was the largest rating group in the dataset.

---

## 💰 Price Category Analysis

The books were divided into Low, Medium and High price categories.

- Low-price books: around **195**
- Medium-price books: around **400**
- High-price books: around **400**

The Medium and High price categories contained considerably more books than the Low-price category.

---

## 📈 Price vs Rating Analysis

The correlation between **price and rating was approximately 0.03**.

This indicates a very weak relationship between price and rating in this dataset.

The analysis also showed that 5-star books were not necessarily more expensive than 4-star books.

- Average price of 4-star books: approximately **£36.1**
- Average price of 5-star books: approximately **£35.4**

---

## 🔗 Price vs Title Length

The correlation between price and title length was approximately **0.01**.

This indicates that title length has almost no relationship with book price in this dataset.

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was created to present:

- Total number of books
- Average book price
- Average rating
- Average title length
- Price categories
- Rating distribution
- Price vs rating analysis
- Book category analysis

The Power BI dashboard file is available in this repository.

---

## 💡 Key Insights

1. The dataset contains **1,000 books**.
2. The average book price is **£35.07**.
3. The average rating is **2.92 stars**.
4. Price and rating have a very weak relationship.
5. Higher-rated books are not automatically more expensive.
6. Medium and High price categories contain more books than the Low category.
7. Title length has almost no relationship with book price.

---

## 📁 Project Files

| File | Description |
|---|---|
| `02_Books_to_Scrape_Data_Cleaning_Model.ipynb` | Python web scraping, data cleaning and analysis |
| `Scrap_books_data.csv` | Final cleaned dataset |
| `Books to Scrape price and Rating Analysis.pbix` | Power BI interactive dashboard |
| `Capstone_Project_Summary Book to Scrap.pdf` | Project report and analysis |

---

## ▶️ Google Colab

[(https://colab.research.google.com/drive/1qlnwdbYzSA9sNcSBGEF8fHIUNeV5FGE)](https://colab.research.google.com/drive/1qlnwdbYzSA9sNcSBGEF8fHIUNeVF5GE-)

---

## 👩‍💻 Author

**Ratan Ghanghoriya**

Data Analyst | Excel | SQL | Python | Power BI
