# 📊 AI-Powered Exploratory Data Analysis (EDA) using Ollama + Gradio

This project is an AI-powered Exploratory Data Analysis (EDA) web application built using:

- Python
- Gradio
- Pandas
- Matplotlib
- Seaborn
- Ollama LLMs

Users can upload any CSV dataset file, and the application will:

✅ Analyze the dataset  
✅ Handle missing values  
✅ Generate statistical summaries  
✅ Create visualizations automatically  
✅ Use Ollama local LLM models to generate AI insights  

---

# 🚀 Features

- Upload CSV files directly
- Automatic data preprocessing
- Missing value handling
- AI-generated dataset insights
- Histogram visualizations
- Correlation heatmaps
- Local LLM support using Ollama
- Interactive Gradio web UI

---

# 🧠 Supported Ollama Models

You can use any installed Ollama model such as:

- llama3
- mistral
- codellama
- deepseek-r1:1.5b
- gemma2

Check installed models:

```bash
ollama list

Project Structure
project/
│
├── app.py
├── requirements.txt
├── README.md
└── generated_plots/
⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/your-username/your-repo-name.git

cd your-repo-name
2️⃣ Install Python Packages
pip install gradio pandas matplotlib seaborn ollama
3️⃣ Install Ollama

Download and install Ollama:

https://ollama.com

4️⃣ Pull LLM Model

Example:

ollama pull llama3

or

ollama pull mistral
▶️ Run the Application

Start Ollama:

ollama serve

Run Gradio App:

python app.py
🌐 Open Web App

After running, open:

http://127.0.0.1:7860
