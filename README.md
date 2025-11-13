# AI & ML Internship – Task 1  
## Data Cleaning & Preprocessing – Titanic Dataset

This project is part of the **Elevate Labs AI & ML Internship**.  
Task 1 focuses on **data cleaning, handling missing values, encoding, feature scaling, and outlier detection** using the Titanic dataset.

---

## 📌 Objectives
- Import and explore the dataset  
- Handle missing data  
- Encode categorical variables  
- Detect and remove outliers  
- Scale numerical features  
- Save the cleaned dataset  

---

## 🛠️ Tools Used
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📊 Steps Performed

### 1. Load and inspect dataset  
Checked:
- shape  
- data types  
- missing values  
- statistical summary  

### 2. Missing value handling  
- Filled `Age` and `Fare` using median  
- Filled `Embarked` using mode  
- Dropped `Cabin` due to many missing entries  

### 3. Categorical Encoding  
- `Sex` → Label Encoding (0/1)  
- `Embarked` → One-Hot Encoding  

### 4. Outlier Detection  
Used boxplots for `Age` and `Fare`.

### 5. Outlier Removal  
Applied the **IQR method** for:
- Age  
- Fare  

### 6. Feature Scaling  
Standardized:
- Age  
- Fare  
- Pclass  
- SibSp  
- Parch  

### 7. Saved Cleaned Dataset  
Saved at:  
`outputs/cleaned_titanic.csv`

---

## 📁 Project Structure
