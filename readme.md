
# Financial News Sentiment Analyzer

This tool scrapes the latest news for a specific company from Google News and uses a fine-tuned DistilRoBERTa model to calculate an overall sentiment score.

---
## 🔧 Step 1: Create a Virtual Environment
It is recommended to use a virtual environment to keep your global Python installation clean.

### Open your terminal or command prompt and navigate to your project folder:
```bash
cd path/to/your/project
```

### Create the environment:
```bash
# Windows
python -m venv venv

# macOS/Linux
python3 -m venv venv
```

### Activate the environment:
```bash
# Windows
.\venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

---
## 📦 Step 2: Install Dependencies
With your virtual environment active, run:
```bash
pip install -r requirements.txt
```

---
## 📘 Step 3: Running in Jupyter Notebook
If you prefer using a Jupyter Notebook, you need to add your virtual environment as a kernel.

### Install Jupyter:
```bash
pip install notebook ipykernel
```

### Add the Kernel:
```bash
python -m ipykernel install --user --name=venv --display-name "Python (Financial-Env)"
```

### Launch Jupyter:
```bash
jupyter notebook
```

In the Notebook interface, go to:
**Kernel > Change Kernel > Python (Financial-Env)**

---
## 🚀 Usage
Run the script and when prompted, enter a company name (e.g., *Tata Steel*, *Nvidia*). The script will output a consolidated sentiment score based on the latest news headlines.

---
## 📄 About
This project leverages:
- **Google News scraping** for fetching latest headlines
- **Fine-tuned DistilRoBERTa model** for sentiment analysis


