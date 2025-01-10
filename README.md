# Advanced Data Analysis Application

A comprehensive GUI application for data analysis, preprocessing, feature selection, and machine learning built with PyQt5 and scikit-learn.

## Features

- **Data Loading and Export**
  - Support for CSV and Excel files
  - Preview data with basic statistics
  - Export processed data in multiple formats

- **Data Preprocessing**
  - Automatic feature type detection
  - Handle missing values with multiple strategies
  - Scaling options (Standard, MinMax, Robust)
  - Categorical encoding (Label, OneHot, Ordinal)
  - DateTime feature extraction

- **Feature Selection**
  - VIF (Variance Inflation Factor) analysis
  - PCA (Principal Component Analysis)
  - Feature importance visualization
  - Correlation analysis

- **Visualization**
  - Histograms
  - Box plots
  - Scatter plots
  - Correlation matrices
  - PCA plots
  - ROC curves
  - Learning curves

- **Machine Learning**
  - Support for both regression and classification
  - Multiple algorithms (Linear, Random Forest, SVM)
  - Hyperparameter tuning with Grid Search
  - Cross-validation
  - Model performance metrics

## Installation

1. Clone the repository:
```bash
git clone https://github.com/osi020/advanced-data-analysis.git
cd advanced-data-analysis
```

2. Create and activate a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python main.py
```

2. Basic workflow:
   - Load your data using the "Load Data" button
   - Inspect data in the "Data" tab
   - Preprocess data using auto or manual options
   - Perform feature selection if needed
   - Create visualizations in the "Visualize" tab
   - Run analysis in the "Analyze" tab

## Project Structure

```
advanced-data-analysis/
├── core/
│   ├── __init__.py
│   ├── data_processor.py
│   └── model_handler.py
├── gui/
│   ├── __init__.py
│   ├── main_window.py
│   └── dialogs/
│       ├── __init__.py
│       └── feature_stats_dialog.py
├── main.py
├── requirements.txt
└── README.md
```

## Requirements

- Python 3.8+
- See requirements.txt for package dependencies

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
