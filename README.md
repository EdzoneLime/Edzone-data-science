# Edzone-data-science

A Python data science project with notebooks, data pipelines, ML models, and dashboards.

## Project Structure

```
Edzone-data-science/
├── notebooks/        # Jupyter notebooks for exploration and analysis
├── data/
│   ├── raw/          # Raw source data (do not modify)
│   └── processed/    # Cleaned and transformed data
├── pipelines/        # Data ingestion and transformation scripts
├── models/           # Trained ML models and artifacts
├── src/              # Shared Python utility modules
├── dashboard/        # Streamlit / Plotly dashboard code
├── requirements.txt  # Python dependencies
└── README.md
```

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/EdzoneLime/Edzone-data-science.git
cd Edzone-data-science
```

### 2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter
```bash
jupyter notebook
```

## Tech Stack

- **Data**: pandas, numpy
- **ML**: scikit-learn, xgboost, lightgbm
- **Visualization**: matplotlib, seaborn, plotly
- **Dashboard**: streamlit
- **Notebooks**: jupyter

## License

MIT
