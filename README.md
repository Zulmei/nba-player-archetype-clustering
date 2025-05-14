# NBA Player Archetype Clustering

This project analyzes and groups NBA players into archetypes based on their statistical performance during the 2022 season. Using K-Means Clustering and PCA (Principal Component Analysis), players are categorized into distinct roles, helping visualize and understand player types from a data-driven perspective.

---

## Project Files

- `nbakmeansproject.ipynb`: Jupyter Notebook containing the full clustering analysis, visualizations, and results.
- `seasonstats.csv`: Dataset of 2022 NBA player stats used for analysis.
- `NBA Player Archetype Clustering.pdf`: Final project report summarizing the methodology, results, and key findings.

---

## Project Highlights

- **Data Cleaning**: Handled missing values and cleaned player name inconsistencies.
- **Feature Selection**: Focused on key performance stats like Points, Assists, Rebounds, Steals, Blocks, FG%, 3P%, and FT%.
- **Clustering**: Used K-Means Clustering to group players into archetypes.
- **Visualization**: Applied PCA to reduce dimensionality and visualize clusters.
- **Object-Oriented Design**: Implemented `Player` and `PlayerCluster` classes for organized role assignment and cluster management.

---

## Identified Archetypes

1. **High-Usage Scorers & Playmakers**:  
   *Examples*: LeBron James, Giannis Antetokounmpo, Kevin Durant  

2. **Rim-Running Bigs & Defenders**:  
   *Examples*: Joel Embiid, Anthony Davis, Karl-Anthony Towns  

3. **Spot-Up/Role Players**:  
   *Examples*: Eric Gordon, Malik Beasley, Coby White  

4. **Bench/Low-Usage Players**:  
   *Examples*: Isaiah Thomas, Tremont Waters  

---

## Future Work

- Explore more advanced player metrics (e.g., PER, BPM, Win Shares).
- Experiment with a higher number of clusters to identify more specific roles.
- Develop an interactive dashboard to explore player clusters.

---

## Author

**Zulmei Eshaqzaie**  
[GitHub Profile](https://github.com/Zulmei)

---

