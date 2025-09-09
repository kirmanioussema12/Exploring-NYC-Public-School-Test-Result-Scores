# 🏫 NYC Schools SAT Analysis  

## 📌 Project Overview  
This project analyzes **New York City public school SAT data** to identify:  
1. Schools with the **best math results**.  
2. The **top 10 performing schools** based on combined SAT scores.  
3. The **borough with the largest variability** in total SAT scores.  

---

## 📑 Task Requirements  

### 1️⃣ Best Math Schools  
- Identify schools with **math scores ≥ 80% of the maximum score (800)**  
- Save results in a DataFrame called `best_math_schools`  
- Columns:  
  | school_name 🏫 | average_math 📊 |  
- Sort by `average_math` in **descending order**  

---

### 2️⃣ Top 10 Performing Schools  
- Identify the **top 10 schools** based on **combined SAT scores** (math + reading + writing)  
- Save results in a DataFrame called `top_10_schools`  
- Columns:  
  | school_name 🏫 | total_SAT 📈 |  
- Sort by `total_SAT` in **descending order**  

---

### 3️⃣ Borough with Largest SAT Score Variability  
- Find the **borough** with the **largest standard deviation** in `total_SAT`  
- Save results in a DataFrame called `largest_std_dev`  
- Columns:  
  | borough 🌆 | num_schools 🏫 | average_SAT 📊 | std_SAT ⚡ |  
- Include **one row** only  
- Round all numeric values to **two decimal places**  

---

## 🛠️ Tools & Skills  
- 📌 **Python & Pandas**: DataFrames, Grouping, Aggregation, Sorting  
- 📌 **Data Analysis**: Identify top-performing schools & statistical variability  
- 📌 **SAT Data Interpretation**: Understand scores across NYC boroughs  

---

## 🚀 How to Run  
1. Clone the repo  
   ```bash
   git clone https://github.com/kirmanioussema12/Exploring-NYC-Public-School-Test-Result-Scores.git
