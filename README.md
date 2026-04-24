#  EXPERIMENT – 18  
# CORRELATION ANALYSIS AND STATISTICAL VISUALIZATION USING PYTHON  

---

## 👨‍🎓 STUDENT DETAILS  

**Name:** Asit Kumar Srivastava  
**PRN:** 25070123026  
**Batch:** A2 (ENTC)  
**Subject:** Exploratory Data Analysis using Python  

---

##  AIM  

To perform correlation analysis and statistical visualization using Python in order to identify relationships between variables in a dataset.

---

## 🎓 OBJECTIVES  

• To understand correlation between variables  
• To compute correlation coefficients  
• To visualize relationships using scatter plots  
• To analyze data using statistical techniques  
• To interpret patterns and dependencies in datasets  

---

## 📚 THEORY  

### 🔹 Correlation  

Correlation measures the **strength and direction of relationship** between two variables.

Range:
- +1 → Strong positive correlation  
- 0 → No correlation  
- -1 → Strong negative correlation  

---

### 🔹 Types of Correlation  

• Positive Correlation → Both variables increase together  
• Negative Correlation → One increases while other decreases  
• Zero Correlation → No relationship  

---

### 🔹 Correlation Coefficient  

Calculated using:

```python
df.corr()
```

---

### 🔹 Scatter Plot  

Used to visualize relationship between two variables.

---

### 🔹 Heatmap  

Used to represent correlation matrix using color intensity.

---

## 🧠 METHODOLOGY / IMPLEMENTATION  

### 🔸 Step 1: Dataset Creation / Loading  

Dataset includes multiple numerical attributes such as:
- Feature variables  
- Dependent variables  

---

### 🔸 Step 2: Data Inspection  

```python
df.head()
df.info()
```

---

### 🔸 Step 3: Correlation Calculation  

```python
df.corr()
```

---

### 🔸 Step 4: Scatter Plot Visualization  

```python
plt.scatter()
```

Used to analyze relationships between variables.

---

### 🔸 Step 5: Heatmap Visualization  

```python
sns.heatmap()
```

Used to visualize correlation matrix.

---

### 🔸 Step 6: Interpretation  

Analyze:
• Strong correlations  
• Weak relationships  
• Patterns in dataset  

---

## ⚙️ KEY LIBRARIES USED  

```python
pandas
numpy
matplotlib.pyplot
seaborn
```

---

## 📊 OBSERVATIONS  

• Correlation values indicate relationships between variables  
• Heatmaps provide quick visual understanding of data  
• Scatter plots help identify trends and patterns  
• Some variables show strong dependency  
• Visualization improves interpretability of statistical results  

---

## ✅ RESULT  

Correlation analysis and statistical visualization were successfully performed.  
Relationships between variables were identified and interpreted using graphical and numerical methods.

---

## 💡 LEARNING OUTCOMES  

• Understood correlation concepts  
• Learned how to compute correlation matrices  
• Visualized relationships using plots  
• Improved analytical thinking for data interpretation  

---

## 🔍 PROJECT SIGNIFICANCE  

This experiment demonstrates how statistical analysis and visualization techniques help in understanding relationships between variables, which is essential for data analysis and machine learning applications.

---

## 📎 SOURCE CODE  

Complete implementation is available in this repository.  

---
