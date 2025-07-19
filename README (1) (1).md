
# 🏅 Olympic Football Men’s Top Scorers – Web Scraping & Analysis
![Image](https://github.com/user-attachments/assets/6d3e9a7f-e161-4227-be4b-0c3c543efac2)
## 📌 About
This project demonstrates how to **automate the collection and analysis of Olympic Men’s Football top scorers data** by scraping live stats from BBC Sport.

Built in **Python**, the script:
- Scrapes player statistics (names, teams, goals scored) with `requests` and `BeautifulSoup`
- Cleans and structures the data using `pandas`
- Visualizes results with `matplotlib`

The result is a dynamic, reproducible workflow that transforms raw web data into insights.

## 🎯 Project Goals
- **Automate data collection**: Eliminate manual tracking
- **Enable data-driven insights**: Analyze and visualize player performances
- **Practice web scraping**: Learn Python scraping tools
- **Build a portfolio piece**: Showcase your skills
- **Support real-time updates**: Foundation for auto-updating stats

## 🗂️ Data Sources
- **Website**: BBC Sport Olympic Football Men’s Top Scorers  
- **Saved Dataset**: Olympics Men Top Scorers.xlsx

## ⚙️ How It Works
1. **Web Scraping**  
   - Fetch the BBC Sport page HTML using `requests`  
   - Parse and locate the player stats table with `BeautifulSoup`  
2. **Data Structuring**  
   - Extract player name, team, and goals scored  
   - Clean and organize data into a `pandas.DataFrame`  
3. **Data Export**  
   - Save cleaned data to an Excel file for future use  
4. **Data Analysis & Visualization**  
   - Rank players by goals scored  
   - Generate charts using `matplotlib`

## 📊 Visualizations & Insights
- **All Goal Scorers with Number of Goals** bar chart  
- **Goals vs Assists** comparison for top scorers  
- **Shots Taken vs Goals Scored** to assess efficiency  
- **Team-wise Share of Goals** via pie or grouped bar chart  
- **Top 10 Scorers** highlighted in a dedicated bar chart  

## 🧑💻 Key Learnings
- **Web scraping**: `requests`, `BeautifulSoup`  
- **HTML structure analysis**  
- **Data cleaning & structuring**: `pandas`  
- **Data visualization**: `matplotlib`  
- **Automation & reusability**  
- **Debugging scraping challenges**: dynamic content, missing fields  

## 📈 Example Output
- Cleaned dataset: structured table of top scorers  
- Visuals: bar charts showcasing top goal scorers  

## ✔️ Conclusion
This project showcases how to **automatically collect, clean, and visualize** real-time sports stats using Python. The workflow is **reusable and adaptable** to any live event, making it a powerful learning piece for your data analytics portfolio.




