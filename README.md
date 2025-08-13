💬 Sentiment Analysis Dashboard

An interactive NLP-powered dashboard to analyze and visualize sentiments from text datasets — built with Streamlit + VADER/TextBlob.

✨ Features
📂 CSV Upload — Analyze reviews, tweets, or comments from your dataset

⚡ Real-Time Sentiment Detection — Enter text and get instant classification

📊 Visual Analytics — Pie charts, bar charts, and sentiment statistics

☁ WordClouds — See the most frequent words for each sentiment class

📥 Export Results — Download processed data as CSV

🛠 Customizable — Easily swap sentiment models or visualizations

🖼 Preview
Dashboard View	WordCloud Example

🛠 Tech Stack
Language: Python 🐍

Framework: Streamlit

NLP Models: VADER (NLTK) & TextBlob

Data Processing: pandas

Visualization: matplotlib, seaborn, wordcloud

📂 Project Structure
bash
Copy
Edit
sentiment-analysis-dashboard/
│── app.py              # Main Streamlit app
│── utils.py            # Helper functions & sentiment logic
│── sample_data.csv     # Example dataset
│── requirements.txt    # Dependencies
│── README.md           # Documentation
🚀 Getting Started
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/<your-username>/sentiment-analysis-dashboard.git
cd sentiment-analysis-dashboard
2️⃣ Create Virtual Environment (Optional but Recommended)
bash
Copy
Edit
python -m venv .venv
# Activate (Windows)
.venv\Scripts\activate
# Activate (Mac/Linux)
source .venv/bin/activate
3️⃣ Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the Dashboard
bash
Copy
Edit
streamlit run app.py
📊 Example Output
Sentiment Distribution:

✅ Positive: 60%

😐 Neutral: 25%

❌ Negative: 15%

Live Prediction:

"I absolutely love this product!" → Positive 💚

📜 License
Licensed under the MIT License — you’re free to use, modify, and distribute.
