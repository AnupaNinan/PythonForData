# NYC Public School Test Result Scores Analysis : https://www.datacamp.com/datalab/w/35a0b280-076f-448d-8668-cbb12f80ae50/edit

This project analyzes SAT performance data from public schools in New York City. Using pandas and data visualization techniques, we explore trends in test scores across boroughs, identify top-performing schools, and evaluate variations in performance.

## 📊 Project Objectives

- Identify NYC schools with strong math performance (at least 80% of max SAT math score).
- Determine the top 10 schools based on total SAT scores.
- Find the borough with the **largest standard deviation** in SAT scores — indicating the widest performance gap.

## 📂 Dataset

The dataset includes SAT scores (math, reading, writing) for NYC public schools, along with school names and borough information.

- **Columns Used**:
  - `school_name`
  - `borough`
  - `math`
  - `reading`
  - `writing`

## 🧠 Key Findings

- **Best math schools**: Schools scoring at least 640 out of 800 in math.
- **Top 10 SAT schools**: Based on total SAT scores (math + reading + writing).
- **Performance variability**: Borough with the highest standard deviation in SAT scores identified.

## 📌 Output DataFrames

- `best_math_schools`: Schools with strong math scores.
- `top_10_schools`: Schools with highest combined SAT scores.
- `largest_std_dev`: Borough with highest SAT score variability (includes school count, average, and standard deviation).

## 🛠️ Technologies

- Python 🐍
- pandas 📊
- Jupyter Notebook 📓 (optional)
- matplotlib/seaborn (optional for visualizations)

## 🔍 Future Enhancements

- Add visualizations (bar charts, box plots) for borough-wise score comparisons.
- Merge with demographic or funding data for deeper insights.
