# DATA-ANALYST-TASK-1

# 🧼 Customer Personality Analysis - Data Cleaning Task

## 📖 About the Dataset

**Customer Personality Analysis** is a detailed analysis of a company’s ideal customers. It helps businesses better understand customer behaviors and tailor products and marketing strategies to different customer segments.

Instead of marketing new products to the entire customer base, businesses can use personality segmentation to target the most promising segments—saving time and money while improving outcomes.

## 🧾 Problem Statement

The objective is to clean and prepare a raw dataset for customer personality analysis. This includes handling missing values, duplicates, inconsistent formatting, and ensuring the data is ready for further exploration such as clustering or modeling.

---

## 🧑‍💼 Attributes

### 👥 People
- `ID`: Unique customer identifier  
- `Year_Birth`: Customer’s birth year  
- `Education`: Level of education  
- `Marital_Status`: Marital status  
- `Income`: Yearly household income  
- `Kidhome`: Number of children in the household  
- `Teenhome`: Number of teenagers in the household  
- `Dt_Customer`: Enrollment date  
- `Recency`: Days since last purchase  
- `Complain`: 1 if the customer complained in the last 2 years

---

## 🧹 Data Cleaning Steps

- ✅ Removed **24 rows** with missing values in the `Income` column  
- ✅ Checked and confirmed **no duplicate rows**  
- ✅ Standardized `Dt_Customer` to datetime format  
- ✅ Title-cased inconsistent values in `Education` and `Marital_Status`  
- ✅ Renamed columns to **lowercase** with **underscores** for consistency  
- ✅ Verified and corrected **data types** (e.g., `income`, `year_birth`)  

---

## 🛠️ Tools Used

- Python  
- Pandas  
- Jupyter Notebook / VS Code  

---

## 🎯 Next Steps

The cleaned dataset can now be used for:
- Customer segmentation using **clustering**
- Predictive modeling
- Visualization dashboards for marketing insights

---

