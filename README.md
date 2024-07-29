# Olympic Games 2024 Match Analysis
Overview

This project aims to provide detailed analysis and visualizations of the matches during the Olympic Games 2024. Using advanced data visualization techniques, such as heatmaps and hexbin plots, we analyze player movements, team strategies, and overall performance.
### Project Structure

    data/: Contains raw and processed data files.
    scripts/: Python scripts for data processing and visualization.
    notebooks/: Jupyter notebooks for interactive analysis.
    images/: Output images of heatmaps and hexbin plots.
    reports/: Generated reports and match summaries.

### Data Collection

We use various APIs and data sources to fetch the required match data. The primary source for player movement and heatmap data is the SofaScore API. The data includes:

    Player positions
    Movement tracks
    Match events (passes, shots, etc.)

### Visualization Techniques
Heatmaps

Heatmaps are used to visualize the density of player movements on the pitch. Individual heatmaps for each player highlight their preferred areas of operation and positioning during the match.
Combined Hexbin Plots

Hexbin plots combine the movements of all players from a team, providing a comprehensive view of the team's strategy and activity zones. This helps in understanding the collective behavior and tactical approaches of the teams.
Key Findings
Australian Team

    Player Movements: Significant activity on the wings, indicating a strategy focused on utilizing the flanks for attacks.
    Team Strategy: Concentration in wide areas suggests reliance on wing play and crossing.

German Team

    Player Movements: Balanced distribution across the pitch, with notable concentration in central areas.
    Team Strategy: Central-oriented attacks with a focus on maintaining possession in midfield.

How to Reproduce the Analysis

    Clone the Repository:

    bash
    git clone https://github.com/doratsolak/Olympic-Games-2024.git
    cd olympic-games-2024

Install Dependencies:

Ensure you have Python installed, then run:

    pip install -r requirements.txt

Fetch Data:

Use the provided scripts to fetch data from the SofaScore API or any other relevant sources.

    python scripts/fetch_data.py

Generate Visualizations:

Run the analysis scripts to generate heatmaps and hexbin plots.

    python scripts/generate_visualizations.py

    View Reports:

    Check the reports/ directory for generated match summaries and visual analysis.



Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.
License

This project is licensed under the MIT License. See the LICENSE file for details.

Contact

For any questions or feedback, please contact Theodora at theodoratsolakidou@gmail.com or connect with me on https://www.linkedin.com/in/theodora-tsolakidou-18884247/.
