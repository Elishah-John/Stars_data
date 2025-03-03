# Stars Analysis Project

## Overview
This project analyzes various properties of stars using Python and data visualization techniques. The analysis explores relationships between different stellar characteristics including temperature, luminosity, radius, and absolute magnitude.

## Features
- Correlation analysis between stellar properties
- Visualization of star characteristics
- Analysis of relationships between:
  - Stellar Radius and Absolute Magnitude
  - Temperature and Luminosity
  - Star Types and various properties

## Dependencies
```
pandas
numpy
matplotlib
seaborn
```

## Key Findings
1. **Strong Correlations**
   - Star type and Absolute magnitude (-0.96): Strong negative correlation
   - Luminosity and Star type (0.67): Strong positive correlation
   - Radius and Star type (0.66): Strong positive correlation

2. **Moderate Correlations**
   - Luminosity and Radius (0.54)
   - Temperature and Luminosity (0.41)
   - Temperature and Star type (0.42)

3. **Weak Correlations**
   - Temperature and Radius (0.07)

## Visualizations
The notebook includes several visualizations:
- Correlation matrix heatmap
- Scatter plot of Radius vs Absolute Magnitude
- Star type distribution plots

## Data Description
The analysis uses a dataset containing the following stellar properties:
- Temperature (K)
- Luminosity (L/Lo)
- Radius (R/Ro)
- Absolute magnitude (Mv)
- Star type

## Usage
1. Ensure all dependencies are installed
2. Open `stars_analysis.ipynb` in Jupyter Notebook or JupyterLab
3. Run all cells to reproduce the analysis

## File Structure
```
.
├── README.md              # Project documentation
├── requirements.txt       # Project dependencies
├── stars_analysis.ipynb   # Main analysis notebook
└── star_data.csv         # Dataset containing star properties
```

## Contributing
Feel free to fork this repository and submit pull requests for any improvements.

## License
This project is open source and available under the MIT License.
