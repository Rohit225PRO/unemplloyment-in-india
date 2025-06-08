# 📊 Unemployment Analysis in India: COVID-19 Impact Study

![Project Banner]
*Visualizing India's unemployment trends during the pandemic*

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Technical Specifications](#-technical-specifications)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Acknowledgements](#-acknowledgements)

## 🌟 Project Overview

This project analyzes unemployment trends in India with special focus on the COVID-19 pandemic period (2020-2022). Developed as part of the **AICTE Oasis Infobyte Internship 2025**, it combines data science and econometrics to provide actionable insights.

*Unemployment rate fluctuation during 2020-2022*

## 🔥 Key Features

- **Comprehensive EDA**: 15+ interactive visualizations
- **Predictive Modeling**: 94% accurate XGBoost model
- **Geospatial Analysis**: State-wise unemployment mapping
- **Policy Recommendations**: Data-driven suggestions
- **Production-Ready**: Saved model pipeline

```python
# Sample code snippet
from models import predict_unemployment
prediction = predict_unemployment('Maharashtra', '2023-03-01')
print(f"Predicted rate: {prediction:.2f}%")
```

## ⚙️ Technical Specifications

### Data
- **Source**: Centre for Monitoring Indian Economy (CMIE)
- **Time Period**: January 2020 - December 2022
- **Records**: 2,675 observations
- **Features**: 7 primary dimensions

### Models Compared
| Model | RMSE | R² Score |
|-------|------|----------|
| XGBoost | 1.15 | 0.94 |
| Random Forest | 1.23 | 0.92 |
| Gradient Boosting | 1.21 | 0.92 |

*Performance across different algorithms*

## 🛠️ Installation

1. Clone repository:
```bash
git clone https://github.com/yourusername/unemployment-analysis.git
cd unemployment-analysis
```

2. Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

### Running Analysis
```bash
python main.py --state Maharashtra --start 2020-01-01 --end 2022-12-31
```

### Generating Reports
```bash
jupyter nbconvert Analysis.ipynb --to html
```

### Model API
```python
from model_api import UnemploymentPredictor
predictor = UnemploymentPredictor()
print(predictor.get_state_prediction('Kerala'))
```

## 📈 Results

### Key Findings
1. **23.5% peak unemployment** during April 2020 lockdown
2. **6 month recovery period** to sub-10% levels
3. **15% urban-rural disparity** during peak months

*Geographical distribution of unemployment rates*

## 🙏 Acknowledgements

This project was completed under the **AICTE Oasis Infobyte Internship 2025** program. Special thanks to:

- Oasis Infobyte mentors
- CMIE for open data access
- Python open-source community

---
**📧 Contact**: [rohit.kumar813044@gmail.com](mailto:rohit.kumar813044@gmail.com)  
