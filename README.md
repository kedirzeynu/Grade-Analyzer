# Class Grade Analyzer

A simple Python data-processing project designed to load, clean, and analyze student exam scores for any class.

## Project Overview

- **Input File:** `class_grades.csv` (contains Student IDs, Midterm scores, and Final exam scores, including intentionally missing scores).
- **Data Cleaning:** Custom Python function that handles blank cells by replacing missing scores with a default value (`0.0`).
- **Data Analysis:** Uses **NumPy** to calculate class averages for Midterm exams, Final exams, and overall performance.

---

## Getting Started

### 1. Clone the Project from GitHub
Make sure [Git](https://git-scm.com/downloads) is installed, then clone the repository and move into it:
```bash
git clone https://github.com/<your-username>/class_grade_analyzer.git
cd class_grade_analyzer
```
Replace `<your-username>` with the GitHub account that hosts the project.

To get later updates, run `git pull` inside the project folder.

### 2. Set Up Virtual Environment
Create and activate a Python virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```
*(On Windows: `venv\Scripts\activate`)*

### 3. Install Dependencies
Install the required packages (`numpy` and `jupyter`):
```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook
Launch Jupyter Notebook in your browser:
```bash
jupyter notebook grade_analyzer.ipynb
```
Select **Kernel > Restart & Run All** to run all cells and view the class grade summary.
