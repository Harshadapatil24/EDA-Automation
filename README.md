# 📊 AutoEDA with Gradio + Ollama (gemma:2b)

Automated Exploratory Data Analysis (EDA) web app using **Gradio** for user interface and **Ollama** with the `gemma:2b` model for generating natural language insights.

---

## 🚀 Features

- 📁 Upload CSV datasets via a sleek Gradio interface
- 📊 Automatic generation of:
  - Summary statistics
  - Data distributions
  - Correlation heatmaps
  - Categorical counts
- 🤖 Natural language insights using `gemma:2b` through [Ollama](https://ollama.com/)
- ⚡ Fast and local — no cloud APIs required


## 🧠 Powered By

- [Gradio](https://gradio.app/) – Interactive UI
- [Pandas](https://pandas.pydata.org/) – Data manipulation
- [Seaborn](https://seaborn.pydata.org/) – Visualization
- [Matplotlib](https://matplotlib.org/) – Plotting
- [Ollama](https://ollama.com/) + `gemma:2b` – Language model insights

---

## 📦 Installation

```bash
git clone https://github.com/your-username/autoeda-gradio-ollama.git
cd autoeda-gradio-ollama

# Install dependencies
pip install -r requirements.txt

# Make sure Ollama is installed and running
# https://ollama.com/download
ollama run gemma:2b
