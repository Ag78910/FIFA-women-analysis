# FIFA Women's Football Analysis

This project analyzes women's football player data from FIFA using exploratory data analysis and regression modeling techniques.

## 📂 Project Structure

```
FIFA-women-analysis/
│
├── notebooks/
│   ├── FIFA_Analysis_EN.ipynb     # English notebook
│   └── AnalisisFIFA.ipynb         # Spanish notebook
├── datos/
│   ├── female_players.csv         # Player data
│   └── female_teams.csv           # Team data


## 🧠 Project Goals

- Understand the salary distribution and performance of female players.
- Identify the most influential attributes that determine salary.
- Build predictive models to guide investment in women's football.
- Propose fair strategies to reduce talent concentration across clubs.

## 🛠️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/FIFA-women-analysis.git
   cd FIFA-women-analysis
   ```

2. Install required libraries (if needed):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Run the notebook:
   Open `notebooks/FIFA_Analysis_EN.ipynb` in Jupyter Notebook.

   Ensure the files `female_players.csv` and `female_teams.csv` are inside the `datos/` folder.

## 📊 Data Sources

- [female_players.csv](./datos/female_players.csv)
- [female_teams.csv](./datos/female_teams.csv)

These files contain player and team attributes extracted from FIFA 24 women's data.

## 📈 Models

Two linear regression models were implemented:
- **Individual variables model**: Based on performance, skills, and age.
- **Team variables model**: Based on average team age and prestige.

## 📢 Authors

- Alejandro Galindo Valencia
- Carla Moreno Molina

---

© 2024 | Academic project for Universidad Internacional de La Rioja (UNIR)
