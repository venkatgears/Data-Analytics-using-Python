# 📚 Setup Guide 

This guide will help you set up your environment and run the Jupyter notebooks 

---

## 🔧 Prerequisites

Before you begin, ensure you have:
- **Python 3.8 or higher** installed ([Download here](https://www.python.org/downloads/))
- **pip** (comes with Python) for package management
- **Git** (optional, for cloning the repository)
- A **text editor or IDE** (VS Code, PyCharm, or similar)
- **Jupyter Notebook** or **JupyterLab** (we'll install this)

---

## 📥 Installation Steps

### Step 1: Clone or Download the Repository

**Option A: Using Git**
```bash
git clone git@github.com:venkatgears/Data-Analytics-using-Python.git
cd data-analytics-using-python
```

**Option B: Download ZIP**
- Download the ZIP file from the repository
- Extract it to a folder
- Open PowerShell/Terminal and navigate to the folder

### Step 2: Create a Virtual Environment (Recommended)

A virtual environment isolates your project dependencies.

**On Windows (PowerShell):**
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

**On macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

You should see `(venv)` appear at the start of your terminal line.

### Step 3: Install Required Libraries

Install all dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

This installs:
- **pandas** – Data manipulation and analysis
- **numpy** – Numerical computing
- **matplotlib** – Plotting and visualization
- **seaborn** – Statistical visualization
- **scikit-learn** – Machine Learning
- **plotly** – Interactive visualizations
- **jupyter** – Notebook environment
- **ipython** – Enhanced Python shell

### Step 4: Verify Installation

Test that everything works:

```bash
python -c "import pandas, numpy, sklearn, jupyter; print('✅ All packages installed successfully!')"
```

---

## ▶️ Running the Notebooks

### Start Jupyter Notebook

Navigate to the project folder and run:

```bash
jupyter notebook
```

Or use JupyterLab (more modern interface):

```bash
jupyter lab
```

Your browser will open automatically to `http://localhost:8888`.

### Navigate to Notebooks

1. In the Jupyter interface, click on the **notebooks/** folder
2. Open `Titanic.ipynb` to start with the basics

### Run Cells

- Click a cell and press **Shift + Enter** to run it
- Or click **Cell → Run All** from the menu
- Follow the prompts and practice exercises

---

## 📖 What Each Notebook Covers

1. **Titanic.ipynb** – Introduction to data science concepts using the Titanic dataset
2. **Healthcare_Insurance.ipynb** – Data cleaning and exploratory data analysis with healthcare insurance data
---

## 🐛 Troubleshooting

### Issue: "Python is not recognized"
**Solution:**
- Ensure Python is in your system PATH
- Or use the full path: `C:\Python39\python.exe` (Windows)

### Issue: "pip: command not found"
**Solution:**
- Use `python -m pip install -r requirements.txt` instead

### Issue: "Jupyter command not found"
**Solution:**
```bash
pip install jupyter --upgrade
```

### Issue: Import errors (e.g., "No module named pandas")
**Solution:**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

### Issue: Jupyter doesn't open in browser
**Solution:**
- Check terminal for the URL (usually `http://localhost:8888`)
- Manually copy-paste it into your browser
- Try a different browser if needed

---

## 💡 Tips for Success

1. **Start with the workshop notebook** – It covers all topics in one comprehensive flow
2. **Run cells sequentially** – Don't skip cells; each builds on previous output
3. **Experiment** – Modify code and see what happens
4. **Read error messages** – They often tell you exactly what went wrong
5. **Use practice exercises** – They reinforce learning and build confidence
6. **Take notes** – Comment on interesting findings and insights

---

## 📝 Recommended Workflow

1. **Setup** (15 min)
   - Install Python and dependencies
   - Download and place the dataset
   - Verify Jupyter runs

2. **Learning** (4 hours)
   - Open notebooks in order
   - Work through each section
   - Complete practice exercises
   - Run all cells to see outputs

3. **Exploration** (Ongoing)
   - Modify code and experiment
   - Explore individual topic notebooks
   - Try different visualizations or models

---

## 🎯 Expected Outcomes

After completing this workshop, you will:
- ✅ Load and explore real‑world datasets
- ✅ Clean and preprocess data
- ✅ Create meaningful visualizations
- ✅ Build and evaluate machine learning models
- ✅ Communicate insights with stakeholders
- ✅ Understand the complete data science workflow

---

## 📧 Need Help?

- Check the **troubleshooting** section above
- Review notebook comments for explanations
- Google common error messages
- Consult the [Jupyter documentation](https://jupyter.org/documentation)
- Visit [Stack Overflow](https://stackoverflow.com/) for specific errors

---

