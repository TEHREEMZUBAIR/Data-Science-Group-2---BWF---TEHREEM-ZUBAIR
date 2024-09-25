---

# 📊 CSV Cleaner, Analyzer, and Visualizer

Welcome to the **CSV Cleaner, Analyzer, and Visualizer**! This project is a comprehensive tool that allows users to upload CSV files, ask questions about the data, and visualize the results with tables and charts. Built using **Langchain**, **OpenAI GPT-3**, and **Streamlit**, this project brings together powerful technologies to create an intuitive data analysis interface.

## 🚀 Features

- **CSV Upload**: Easily upload CSV files directly from your local machine.
- **Natural Language Queries**: Pose queries about your data in plain English.
- **Automated Responses**: Get answers from GPT-3 with structured responses, including tables, bar charts, and line charts.
- **Interactive Visualizations**: Visualize data insights with responsive tables and interactive charts.
- **User-Friendly Interface**: Simple, clean interface powered by Streamlit for ease of use.

## 🛠️ Installation

### 1. Set up your environment
To get started, clone this repo and create a virtual environment:
```bash
python -m venv venv
```
Activate it:
```bash
venv\Scripts\activate
```

### 2. Install Dependencies
Install the necessary packages:
```bash
pip install langchain==0.0.146 python-dotenv==1.0.0 streamlit==1.22.0 openai==0.27.7 tabulate==0.9.0
```

### 3. Set Your OpenAI API Key
Get your OpenAI API key [here](https://platform.openai.com/account/api-keys), and then set the environment variable:
```bash
set OPENAI_API_KEY=<YOUR_API_KEY>
```

## 💻 Usage

### 1. Run the Application
To start the application, run:
```bash
streamlit run Talk_with_CSV.py
```

This will open a new tab in your browser with the app's interface. You'll be able to upload a CSV file, type queries, and view the responses with visualizations.

### 2. How It Works
- **Upload CSV**: You’ll be prompted to upload a CSV file.
- **Ask a Query**: Type your query in natural language.
- **Submit Query**: Click the "Submit Query" button to get your answer, along with a table, bar chart, or line chart visualization.

### 3. Available Query Types
You can ask the system for:
- **Tables**: e.g., "Show me the first 10 rows."
- **Bar Charts**: e.g., "Show me a bar chart of sales by product."
- **Line Charts**: e.g., "Plot the trend of prices over time."
- **Text Responses**: e.g., "What is the total number of rows?"

## 📊 Sample Output

After running the app, you will be able to view dynamic tables, bar charts, and line charts based on your CSV data and queries, making data exploration faster and easier.

## 🔗 Key Libraries

- [Langchain](https://langchain.readthedocs.io/en/latest/): Integrating powerful language models.
- [Streamlit](https://streamlit.io/): Building beautiful, interactive data science apps.
- [OpenAI](https://beta.openai.com/): Access to GPT-3 for intelligent query responses.

## 🤝 Contributing

We welcome contributions to improve this tool! Feel free to open issues or submit pull requests.

## 📬 Contact

Feel free to reach out for any questions or suggestions:
- 📧 Email: tehreemzubair785@gmail.com

---