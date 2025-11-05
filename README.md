📊 Live Data Dashboard

A sleek, real-time data visualization app built with Streamlit.
Watch your scores come to life with dynamic bar charts, instant updates, and smart trend insights — all from a simple CSV file.

🚀 Overview

Live Data Dashboard provides real-time visualization and analysis of score data from a CSV file.
You can filter by names, monitor performance trends, and instantly see which scores are rising or falling — all refreshed every 2 seconds.

✨ Key Features
🎯 Interactive Data Filtering: Choose one or multiple names to view specific score sets.
📈 Real-Time Visualization: Live bar charts update automatically every 2 seconds.
🧮 Instant Insights: See average, maximum, and minimum scores for selected data.
🔍 Trend Detection: Highlights which scores are going up or down since the last refresh.
💾 Smart Session State: Remembers previous data for accurate trend tracking.

💡 Use Cases
Tracking real-time performance or test scores
Monitoring live metrics in dashboards
Visualizing fast-changing data for quick insights

⚙️ How It Works
The app reads a CSV file containing name and score columns.
Users select which names to view.
The dashboard calculates key statistics and displays an interactive bar chart.
Changes from the previous data are highlighted to show trends.
The page refreshes automatically every 2 seconds for live updates.

🧰 Requirements
Python 3.x
Streamlit
Pandas

🔧 Installation
# Clone the repository
git clone https://github.com/yourusername/live-data-dashboard.git
cd live-data-dashboard

# Install dependencies
pip install streamlit pandas

# Run the app
streamlit run app.py


(Make sure to update the file_path variable with your CSV file location.)

💫 Why You’ll Love It
Simple setup. Real-time visuals. Instant insights.
Perfect for anyone who wants a live, interactive look at their data — from students to analysts.
