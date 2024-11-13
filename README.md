NBA Exploratory Data Analysis (EDA) Project
Project Overview
This project analyzes the potential impact of Jared McCain’s three-point shooting on the Philadelphia 76ers' team performance, using real NBA player and team statistics. Additionally, it explores how integrating high-performance players could impact team shooting percentages and overall efficiency. By leveraging Python's data science libraries, this project offers insights into the ways a player’s shooting proficiency can affect team dynamics and win potential over a season.

Project Structure
data/

raw/: Contains raw data files like jared_mccain_3p.csv and sixers_3p.csv.
cleaned/: Stores cleaned data used for analysis (cleaned_data.csv).
notebooks/

nba_eda.ipynb: Jupyter notebook with detailed data analysis, including data cleaning, visualization, and statistical insights.
src/

data_processing.py: Cleans and prepares raw data for analysis.
analysis.py: Contains the main analysis functions and visualizations.
visualizations.py: Generates various plots and charts for insights.
Getting Started
Prerequisites
Python 3.x
Python packages:
pandas (for data manipulation)
matplotlib and seaborn (for visualization)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/nba-eda-project.git
cd nba-eda-project
Install dependencies:
bash
Copy code
pip install pandas matplotlib seaborn
Project Workflow
Data Collection: Raw data on player (Jared McCain) and team (Philadelphia 76ers) statistics is stored in the data/raw folder.
Data Processing: Run data_processing.py to clean and preprocess the data.
bash
Copy code
python src/data_processing.py
Data Analysis: Run analysis.py to perform statistical analysis on the data.
bash
Copy code
python src/analysis.py
Visualizations: Generate visualizations by running visualizations.py.
bash
Copy code
python src/visualizations.py
Exploratory Notebook: View detailed analysis and findings in the nba_eda.ipynb notebook.
Key Insights
Impact on Team Shooting: Jared McCain’s three-point shooting is projected to improve the Philadelphia 76ers’ three-point percentage, potentially raising it from 36.3% to over 38%.
Player Synergy: Hypothetical analyses on adding star players suggest complementary skill sets could improve offensive efficiency and team performance.
Files
data/raw/jared_mccain_3p.csv: Contains Jared McCain’s three-point shooting stats.
data/raw/sixers_3p.csv: Philadelphia 76ers' team shooting data for the 2023-2024 season.
data/cleaned/cleaned_data.csv: Cleaned data used for analysis.
Technologies
Python: Core programming language.
Jupyter Notebook: For interactive analysis.
pandas: Data manipulation and cleaning.
matplotlib & seaborn: Data visualization.
Results and Findings
The analysis suggests that Jared McCain’s shooting could have a measurable positive impact on the Philadelphia 76ers' overall team shooting efficiency. Additional analysis highlights how star players' synergies can influence team dynamics and win potential over a season.

Future Improvements
Integrate more players' stats for a deeper team synergy analysis.
Incorporate machine learning to predict performance based on team composition.
Expand the data to cover more seasons for a longitudinal study.
Author
Selorm Essey
