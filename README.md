# airline-market-insights
Approach Description: I used a free API (aviationstack) to fetch live flight data, processed it using pandas to identify popular routes, and visualized it with Plotly. I integrated Hugging Face’s transformers summarization pipeline to extract AI-generated insights. The app is built with Streamlit for easy deployment and use.
# ✈️ Airline Market Demand Web App
📦 Folder Structure
airline-market-demand-app/
├── app.py
├── fetch_data.py
├── process_data.py
├── summary_ai.py
├── requirements.txt
└── README.md
## 🔍 Description

This project is a Streamlit web application that fetches airline flight data via a public API, processes it to identify popular routes, and uses AI (transformers) to summarize key insights.

It is designed for hostel businesses in Australia to monitor airline booking trends and make better travel-related decisions.

## 🛠️ Features

- Fetches live flight data using the aviationstack API
- Identifies top 10 most popular flight routes
- Generates natural-language AI summaries of the data
- Displays results in a clean, interactive dashboard

## 🚀 How to Run Locally

```bash
git clone https://github.com/YOUR_USERNAME/airline-market-demand-app.git
cd airline-market-demand-app
pip install -r requirements.txt
streamlit run app.py
🧠 AI Summary Model
Uses Hugging Face model: sshleifer/distilbart-cnn-12-6 from transformers library.

📊 Tools Used
Python
Streamlit
Transformers
Pandas
Plotly
Requests


