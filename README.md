# FIFA Women's Football Analysis

This project presents a complete exploratory and predictive analysis of women's football player data using FIFA datasets.

##  Project Structure

```
FIFA-women-analysis/
│
├── FIFA_Analysis_EN_Final.ipynb     # Final notebook with extended analysis and conclusions
├── female_players.csv               # Player-level dataset
├── female_teams.csv                 # Team-level dataset
├── README.md                        # Project documentation
├── requirements.txt                 # Python dependencies
```

##  Project Overview

This notebook contains:
- Exploratory data analysis (EDA) on player demographics, salaries, and team data.
- Visualizations: histograms, scatter plots, bar charts, and radar plots.
- Two regression models to analyze the drivers of player salaries:
  - **Individual-based** (performance, age, reputation)
  - **Team-based** (prestige, average age)
- Policy recommendations to promote equity in women's football.

##  Key Findings

- Strong positive correlation between a player's current performance and their salary.
- Team-level variables (prestige, team averages) have minimal impact on salary.
- Tactical attributes vary significantly by position, affecting player valuation.
- Wages are skewed and concentrated among a few nations and clubs.

##  Strategic Recommendations

- Financial aid for under-resourced clubs tied to development goals.
- Strengthening national leagues with policy and investment.
- Regional outreach in underrepresented areas to promote inclusion.

##  How to Run

1. Clone the repo or download the files.
2. Install the requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook FIFA_Analysis_EN_Final.ipynb
   ```

##  Authors

- Alejandro Galindo Valencia  
- Carla Moreno Molina

---

© 2024 | Academic project for Universidad Internacional de La Rioja (UNIR)
