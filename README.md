## Olympics Data Analysis Web App
A comprehensive, interactive web application built with Python and Streamlit to explore 120 years of Olympic history. This project transforms raw historical data into actionable insights through various visualizations, including medal tallies, country performances, and athlete demographics.

# 🛠️ Features
- Overall Analysis: High-level statistics on editions, host cities, sports, and participating nations.
- Medal Tally: Interactive leaderboard filterable by year and country.
- Country-wise Analysis: Trend lines of medal wins and heatmaps showing sport-specific dominance.
- Athlete-wise Analysis: Age distribution plots and Height vs. Weight correlations across different sports.

# 📂 Project Structure
.
├── app.py              # Main Streamlit application UI
├── helper.py           # Data processing and analysis functions
├── preprocessor.py     # Data cleaning and merging logic
├── athlete_events.csv  # Raw dataset: Athlete information
├── noc_regions.csv     # Raw dataset: Region/NOC mapping
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation

# 🔧 Installation & Setup
Clone the repository:
git clone https://github.com/[YourUsername]/olympic-data-analysis.git
cd olympic-data-analysis

Install dependencies:
pip install -r requirements.txt

Run the app:
treamlit run app.py

# 📊 Tech Stack
Language: Python 3.x

Web Framework: Streamlit

Data Manipulation: Pandas, NumPy

Visualization: Plotly, Seaborn, Matplotlib

# 📚 Resources & Acknowledgments
Original Tutorial: Olympics Data Analysis | Data Analysis Project | Machine Learning with Deployment by CampusX.

Source Code: GitHub Repository by Nitish Singh.

Dataset: 120 years of Olympic history
