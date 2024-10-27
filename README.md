
### Project Description

**Valorant Pro Players Settings Analysis**

This project involves the extraction, analysis, and visualization of data related to the settings used by professional Valorant players. The dataset was scraped from prosettings.com and includes various configurations such as mouse sensitivity, DPI, crosshair settings, and other game-specific preferences. The goal of this analysis is to uncover patterns and trends among the settings used by top players, which can be beneficial for the broader gaming community.

### README.md

```markdown
# Valorant Pro Players Settings Analysis

## Overview
This project focuses on the analysis of settings used by professional Valorant players. The data was scraped from prosettings.com and includes various configurations such as mouse sensitivity, DPI, crosshair settings, and other game-specific preferences. The aim is to identify patterns and trends that can help players optimize their own settings based on what the pros are using.


## Dataset
The dataset contains settings data for professional Valorant players, including:
- Player Name
- Team
- Mouse Sensitivity
- DPI
- EDPI
- Hz
- Resolution
- Aspect Ratio
- FOV
- Crosshair Settings
- Keybinds

## Installation
To run the analysis locally, you need to have Python and Jupyter Notebook installed. Follow the steps below to set up the environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/valorant-pro-players-settings-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd valorant-pro-players-settings-analysis
   ```

3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the Jupyter Notebook and start the analysis, use the following command:
```bash
jupyter notebook
```
Open the `Valorant_Pro_Players_Settings_Analysis.ipynb` notebook to view and run the analysis.

## Project Structure
The project directory contains the following files and folders:
- `Valorant_Pro_Players_Settings_Analysis.ipynb`: Jupyter Notebook containing the analysis.
- `data/`: Directory containing the scraped dataset.
- `scripts/`: Python scripts used for data scraping and preprocessing.
- `images/`: Directory containing images and visualizations generated from the analysis.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python packages.

## Analysis and Findings
The analysis includes the following steps:
1. Data Cleaning: Removing duplicates and handling missing values.
2. Data Exploration: Summary statistics and distribution plots for various settings.
3. Visualization: Scatter plots, histograms, and box plots to visualize patterns and trends.
4. Insights: Key takeaways from the analysis, such as common settings among top players.



