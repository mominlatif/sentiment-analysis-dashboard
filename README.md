📊 Sentiment Analysis Dashboard
An interactive dashboard built with Streamlit for performing sentiment analysis on text data such as reviews, tweets, or comments.
Supports CSV uploads, real-time text input, visualizations, and downloadable results.

🚀 Features
✅ Upload CSV dataset and auto-analyze sentiments
✅ Real-time text input for sentiment detection
✅ Positive / Neutral / Negative classification
✅ Interactive bar chart, pie chart, and sample viewer
✅ Optional WordCloud generation
✅ Download analyzed dataset as CSV
✅ Modular, clean Python code (easy to customize)

🛠️ Tech Stack
Python 3.8+

Streamlit for dashboard UI

VADER (NLTK) & TextBlob for sentiment scoring

pandas, matplotlib, seaborn, wordcloud for data processing & visualization

📂 Project Structure
bash
Copy
Edit
sentiment-analysis-dashboard/
│── app.py              # Main Streamlit app  
│── utils.py            # Sentiment analysis logic & helpers  
│── sample_data.csv     # Example dataset  
│── requirements.txt    # Required dependencies  
│── README.md           # Project documentation  
📦 Installation & Running
bash
Copy
Edit
# 1. Clone the repository
git clone https://github.com/<your-username>/sentiment-analysis-dashboard.git
cd sentiment-analysis-dashboard

# 2. (Optional) Create virtual environment
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the dashboard
streamlit run app.py
📊 Example Output
Sentiment Distribution

Positive: 60%

Neutral: 25%

Negative: 15%

Live Input Example

"I absolutely love this product!" → Positive

📝 License
This project is licensed under the MIT License – feel free to use and modify with attribution.

