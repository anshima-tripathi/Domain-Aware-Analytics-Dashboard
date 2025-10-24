# 🌐 Domain-Aware Analytics Dashboard



> \*\*AI-powered, domain-aware analytics pipeline\*\* that automates data profiling, dashboard generation, and visualization — built with Python + Streamlit + LLMs.



---



## ✨ Overview



The \*\*Domain-Aware Analytics Dashboard\*\* empowers data teams to transform raw CSV files into interactive, AI-curated dashboards with \*\*zero manual setup\*\*.  

By combining \*\*Large Language Models (LLMs)\*\* with \*\*data profiling\*\*, it intelligently identifies patterns, suggests KPIs, and auto-generates insightful visualizations.



---



## ⚙️ Clone and Setup Pipeline



```bash

# Clone the repository

git clone <repository-url>

cd ai-analytics-dashboard



# Create and activate a virtual environment

python -m venv venv

source venv/bin/activate   # On Windows: venv\\Scripts\\activate



# Install dependencies

pip install -r requirements.txt

🚀 Run the Pipeline

bash

Copy code

# Run the end-to-end analytics pipeline

python main.py your-file.csv

📊 Launch Dashboard Only

bash

Copy code

# Run Streamlit UI only

streamlit run dashboard\_app.py

🏗️ Architecture

The pipeline follows SOLID design principles, ensuring modularity, scalability, and clean separation of concerns.



pgsql

Copy code

📦 AI Analytics Dashboard Pipeline
```bash
├── 🔧 Data Processing Layer

│   ├── CSVDataLoader - Handles file reading, encoding detection, preprocessing

│   └── DataProfiler - Analyzes data types, patterns, and quality

├── 🤖 AI Analysis Layer

│   └── LLMClient - Generates dashboard plans using OpenAI/HuggingFace

├── 📊 Visualization Layer

│   └── ClassicDashboard - Renders interactive Streamlit dashboard

└── ⚙️ Configuration Layer

&nbsp;   └── ConfigManager - Manages settings and API keys
```
🧩 Project Structure

graphql

Copy code

.
```bash

├── config/

│   └── settings.yaml          # Configuration file

├── dashboard\_app.py           # Main Streamlit dashboard

├── data/

│   ├── raw/                   # Original CSV files

│   ├── processed/             # Cleaned data

│   └── cache/                 # Temporary files

├── main.py                    # Pipeline orchestrator

├── outputs/

│   ├── dashboard\_plan.json    # AI-generated dashboard config

│   ├── profile\_summary.json   # Data analysis results

│   └── dashboard\_cache.json   # Cached AI responses

├── src/

│   ├── config.py              # Configuration management

│   ├── data\_loader.py         # CSV loading and preprocessing

│   ├── data\_profiler.py       # Data analysis and profiling

│   └── llm\_client.py          # AI client for dashboard generation

└── requirements.txt
```
🧠 Core Capabilities

✅ Automated Data Profiling

✅ Schema Detection \& Missing Value Analysis

✅ AI-driven Dashboard Blueprint via LLMs

✅ Interactive Visualizations with Streamlit

✅ Modular \& Extensible Pipeline Design



📷 Dashboard Preview

Automated Insights	Interactive Charts



Data Profiling Summary	Dynamic KPI Suggestions



🧑‍💻 Tech Stack

Python 3.10+



Streamlit



Pandas, NumPy



OpenAI / HuggingFace API



PyYAML, JSON



Plotly / Matplotlib



👩‍🎤 Author

Anshima Tripathi

Data Scientist | AI Engineer | Data Analytics Enthusiast



📬 Email: anshimatripathi2003@gmail.com

🔗 LinkedIn: linkedin.com/in/anshima-tripathi-70863221b



⭐ Contribute

Pull requests are welcome!

If you'd like to improve the pipeline or add new visual components, open an issue or submit a PR.



🏁 License

This project is open-source and available under the MIT License.

