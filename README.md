# Lab 8: The Data Pipeline – From Raw JSONs to Master CSV

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/drive/1_3FQR944BKULJhk1juIJjduvjMS7zBHq?usp=sharing)

---

## 📖 Story Point  
Our firm just received raw JSON files for each match. Before any analysis, we need a robust pipeline to consolidate this into a structured master dataset.  

---

## 🎓 Mapping to Lecture  
- **Topic:** Advanced Data Preprocessing, Data Engineering  
- **Python Libraries:** `pandas`, `json`, `glob`, `os`  
- **Category:** Data Engineering  

---

## 🧪 In-Class Practical  

**Objective:**  
Write a Python script to parse all JSONs & aggregate over-by-over data into a single CSV.  

**Tasks:**  
1. Use `glob` to list JSON files in `raw_match_data/`  
2. Loop through each & load JSON  
3. Extract `matchId` & `wormAndManhattan`  
4. Parse overs → cumulative runs & wickets  
5. Append dictionaries to master list  
6. Convert into Pandas DataFrame & save as CSV  

---

## 🏡 Home Task  
- Write a short summary of your CSV structure  
- Identify **2 possible real-world data issues** (e.g. missing keys, incomplete matches)  

---

## ✅ Deliverable  
A Jupyter Notebook & the final `multi_match_over_by_over.csv` file.  

---

## ⚙ Requirements  
Install required libraries:  
`!pip install -r requirements.txt`
