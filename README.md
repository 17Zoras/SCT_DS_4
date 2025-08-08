# SCT_DS_4
# Task 4 – Time Analysis of US Accidents Dataset

This project performs **time-based analysis** on the **US Accidents (2016–2023)** dataset. It focuses on understanding accident patterns based on:

- **Hour of the Day**
- **Day of the Week**

This helps identify high-risk timeframes and can be useful for urban planners, traffic departments, and public safety initiatives.

---

## ​ Dataset Used

**Name:** US Accidents (2016–2023)  
**Source:** [Kaggle – US Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) :contentReference[oaicite:0]{index=0}  
**Note:** Download the dataset manually from Kaggle and place the `US_Accidents_March23.csv` file in the same directory as the script or notebook.

---

## ​ What the Script Does

1. **Loads the dataset** using `pandas`  
2. **Parses the `Start_Time` column** to extract:  
   - Hour of the day (0–23)  
   - Day of the week (Monday–Sunday)  
3. **Visualizes**:  
   - A bar chart of accident counts per hour  
   - A bar chart of accident counts per day of the week

---

## ​ Technologies Used

- Python 3.x  
- Jupyter Notebook / Python Script  
- `pandas` for data analysis  
- `matplotlib` and `seaborn` for visualization

---

## ​ How to Run the Code

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/Task4_TimeAnalysis.git
   cd Task4_TimeAnalysis
