# FIFA Player Stats Dashboard

This project is a **Dash** web application for visualizing and comparing FIFA players' stats using interactive charts and dashboards. The app allows users to view individual player stats, compare multiple players across various metrics, and visualize data in different forms such as bar charts, line charts, radar charts, and pie charts.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Features](#features)
- [How to Run](#how-to-run)
- [Acknowledgements](#acknowledgements)

## Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MohamedGuedira/FIFA-Players-Stats-And-Comparison.git
    cd FIFA-Players-Stats-And-Comparison
    ```

2. **Install the required dependencies**:
    The project uses several Python libraries like `dash`, `dash-bootstrap-components`, `plotly`, and `pandas`. You can install the dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```
    If you don't have a `requirements.txt` file, you can install the dependencies manually:
    ```bash
    pip install dash dash-bootstrap-components pandas plotly
    ```

3. **Prepare the dataset**:
    Ensure you have the dataset file (`fifa_players.csv`) in the root directory of the project. This file contains the data that will be visualized in the dashboard.

## Usage

This dashboard provides two main pages:
1. **Player Stats Page**: Users can select a player and view their performance across different skill categories, visualized with bar, pie, and line charts.
2. **Player Comparison Page**: Users can compare two players across various attributes using radar charts, bar charts, and line charts.


## Features

- **Interactive Dropdowns**: Select players from a dropdown menu to visualize their stats.
- **Multiple Chart Types**:
  - Bar charts
  - Pie charts
  - Line charts
  - Radar charts (for comparison)
- **Player Comparison**: Compare two players side-by-side across all skill metrics.

### Key Stats Available:
- Crossing
- Finishing
- Heading Accuracy
- Short Passing
- Dribbling
- Speed
- Strength
- Reactions
- Positioning
- Vision, and more.

## How to Run

1. After installation and setup, you can run the Dash app by executing the following command:
    ```bash
    python app.py
    ```

2. The application will be hosted on `http://127.0.0.1:8070/` or the specified port in the code.

3. Navigate to this URL in your browser to interact with the dashboard.

## Acknowledgements

This project uses the following open-source libraries:
- **Dash** for building interactive web applications in Python.
- **Plotly** for creating charts and visualizations.
- **Dash Bootstrap Components** for responsive layout and styling.
- **Pandas** for data manipulation and analysis.

Feel free to contribute or report any issues.


