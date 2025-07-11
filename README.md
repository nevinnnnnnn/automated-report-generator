# 📊 Automated Report Generator

## 🎯 Objective  
Automatically generate a **sales performance report** (PDF/HTML) using Python, running on GitHub Actions.

## 📂 Project Structure  
- `data/`: Input datasets (CSV).  
- `scripts/`: Python scripts for cleaning, analysis, and report generation.  
- `outputs/`: Generated reports (PDF/HTML).  
- `.github/workflows/`: GitHub Actions automation.  

## ⚙️ How It Works  
1. Data is pulled from a CSV (or API).  
2. Python processes it and generates visualizations.  
3. A PDF/HTML report is created and saved in `outputs/`.  
4. Scheduled via **GitHub Actions** (runs weekly).  
