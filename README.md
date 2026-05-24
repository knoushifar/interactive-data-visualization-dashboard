# Interactive Data Visualization Dashboard

A portfolio-ready Python data visualization project featuring exploratory analysis and interactive Plotly charts exported as standalone HTML files.

## Project Overview

This project focuses on transforming exploratory data analysis into clear, interactive visual outputs. The notebook contains the analysis workflow, while the exported HTML files make the visualizations easy to open, share, and review without running the notebook.

The project is suitable for demonstrating:
- exploratory data analysis
- interactive visualization design
- distribution and clustering patterns
- comparison charts
- dashboard-style presentation of results

## Key Features

- Jupyter Notebook analysis workflow
- Interactive Plotly visualizations
- Standalone HTML charts that can be opened in any browser
- Organized repository structure for GitHub
- Portfolio-focused documentation

## Visualizations Included

| File | Description |
|---|---|
| `visualizations/clustered.html` | Cluster-based visualization for comparing grouped patterns |
| `visualizations/subplot.html` | Multi-panel subplot visualization |
| `visualizations/boxplot.html` | Box plot for distribution and outlier analysis |
| `visualizations/dropdown.html` | Interactive chart with dropdown controls |
| `visualizations/heatmap.html` | Heatmap for relationship or intensity analysis |
| `visualizations/normal_histogram_plot.html` | Histogram with normal distribution-style view |
| `visualizations/histogram_plot.html` | Standard histogram for distribution analysis |

## Repository Structure

```text
interactive-data-visualization-dashboard/
│── notebooks/
│   └── analysis.ipynb
│── visualizations/
│   ├── clustered.html
│   ├── subplot.html
│   ├── boxplot.html
│   ├── dropdown.html
│   ├── heatmap.html
│   ├── normal_histogram_plot.html
│   └── histogram_plot.html
│── docs/
│   └── visualization_index.html
│── README.md
│── requirements.txt
│── .gitignore
│── LICENSE
```

## How to Run the Project

Clone the repository:

```bash
git clone https://github.com/knoushifar/interactive-data-visualization-dashboard.git
cd interactive-data-visualization-dashboard
```

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook notebooks/analysis.ipynb
```

## How to View the Visualizations

You can open each file inside the `visualizations/` folder directly in a browser.

For easier navigation, open:

```text
docs/visualization_index.html
```

## Skills Demonstrated

- Python programming
- exploratory data analysis
- interactive data visualization
- Plotly dashboard-style charting
- statistical distribution analysis
- GitHub project organization

## Possible Improvements

Future improvements could include:
- adding the original dataset if redistribution is allowed
- adding a dashboard app using Streamlit or Dash
- adding written interpretation for each chart
- adding screenshots of the visualizations to the README

## License

This project is licensed under the MIT License.
