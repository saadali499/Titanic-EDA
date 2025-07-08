# 🚢 Titanic EDA - Exploratory Data Analysis

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**. The objective is to uncover hidden patterns and insights related to passenger survival.

---

## 📁 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- File used: `train.csv`

---

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

---

## 📋 Project Workflow

1. **Loading the Dataset**
2. **Inspecting the Structure & Summary Statistics**
3. **Missing Data Analysis**
4. **Cleaning the Dataset**
   - Fill missing `Age` values with median
   - Fill missing `Embarked` with mode ('S')
   - Drop `Cabin` due to high missingness
5. **Univariate Analysis**
   - Distribution of passengers by class, gender, survival
6. **Bivariate Analysis**
   - Survival by gender
   - Survival by class
   - Age vs survival
7. **Conclusion & Insights**

---

## 📊 Key Insights

- **Females** had a significantly higher survival rate than males.
- **First-class passengers** had better survival outcomes than those in lower classes.
- **Younger passengers**, particularly children, were more likely to survive.
- `Sex`, `Pclass`, and `Age` were strong indicators of survival.

---

## 📂 Project File

- `Titanic_EDA.ipynb` – Contains full analysis, visuals, and interpretation in Jupyter Notebook.

---

## 🙋‍♂️ Author

**Muhammad Saad Ali**  
📧 saadali.499@gmail.com  
🔗 [GitHub Profile](https://github.com/saadali499)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/muhammad-saad-ali-a78188337/)

---

## 💡 Future Work

This EDA forms the foundation for:
- Machine learning model building
- Feature engineering for predictive tasks
- Real-time dashboard development using Streamlit

---

*If you found this project useful, feel free to ⭐ the repository or connect with me on LinkedIn!*
