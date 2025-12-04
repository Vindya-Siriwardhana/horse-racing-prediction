# Horse Racing Performance Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Latest-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

## 📊 Project Overview

A comprehensive data science project analyzing **777,549 horse racing records** spanning 7 years (2015-2022) to predict race outcomes and develop optimal betting strategies. This project demonstrates end-to-end data analysis, statistical modeling, machine learning implementation, and financial performance evaluation.

**Key Achievement:** Developed predictive models and rating systems that could inform data-driven betting strategies in horse racing markets.

---

## 🎯 Business Problem

Horse racing betting markets rely heavily on subjective assessments and historical performance. This project aims to:
- Identify peak performance age for racehorses
- Develop objective rating systems for horse performance
- Build predictive models for race outcomes
- Compare model performance against market odds

---

## 📁 Project Structure

```
horse-racing-prediction/
│
├── notebooks/
│   ├── horse_racing_analysis_Q0_Q1_Q2.ipynb    # Data exploration & rating systems
│   ├── horse_racing_analysis_Q3.ipynb           # Predictive modeling
│   └── horse_racing_analysis_Q4.ipynb           # Market comparison analysis
│
├── report/
│   └── Horse_Racing_Report.html                 # Comprehensive analysis report
│
├── data/
│   └── [Generated intermediate datasets]
│
└── README.md
```

---

## 🔍 Analysis Components

### Q0: Data Exploration & Preprocessing
- **Dataset:** 777,549 racing records across 7 years
- **Features:** 30 variables including horse characteristics, race conditions, performance metrics
- **Data Quality:** Missing value handling, outlier detection, feature engineering
- **Time Period:** May 2015 - April 2022

### Q1: Peak Age Analysis
- Statistical analysis of horse performance across different ages
- Identification of optimal racing age windows
- Performance degradation patterns
- Career trajectory analysis

### Q2: Rating Systems Development
- **Custom Rating System:** Developed proprietary horse performance metrics
- **Comparative Analysis:** Benchmarked against existing rating systems
- **Feature Engineering:** Created composite performance indicators
- **Validation:** Cross-validation against historical outcomes

### Q3: Predictive Modeling
- **Models Implemented:**
  - Logistic Regression (baseline)
  - Random Forest Classifier
  - Gradient Boosting (XGBoost)
  - Neural Networks
  
- **Model Evaluation:**
  - Accuracy, Precision, Recall, F1-Score
  - ROC-AUC analysis
  - Feature importance analysis
  - Cross-validation performance

### Q4: Market Comparison
- **Comparison with betting odds** (market predictions)
- **Value betting opportunities** identification
- **ROI analysis** of model-based strategies
- **Risk-adjusted returns** evaluation

---

## 🛠️ Technologies & Tools

**Programming & Analysis:**
- Python 3.8+
- Pandas, NumPy (data manipulation)
- Scikit-learn (machine learning)
- XGBoost (gradient boosting)
- Statsmodels (statistical analysis)

**Visualization:**
- Matplotlib
- Seaborn
- Plotly (interactive charts)

**Environment:**
- Jupyter Notebook
- Anaconda

---

## 📈 Key Findings

### Performance Insights:
- Identified optimal racing age range for peak performance
- Developed rating system with strong predictive power
- Created feature set that outperforms traditional metrics

### Model Performance:
- **Best Model:** [Your best performing model]
- **Accuracy:** [Your accuracy metric]
- **ROC-AUC:** [Your AUC score]
- **Market Comparison:** Models identified value opportunities not reflected in market odds

### Business Impact:
- Quantified factors most influential in race outcomes
- Identified systematic biases in market pricing
- Provided data-driven framework for performance assessment

---

## 🚀 How to Run

### Prerequisites
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn statsmodels jupyter
```

### Execution Order
**IMPORTANT:** Notebooks must be run sequentially as each generates data for the next:

1. **First:** Run `horse_racing_analysis_Q0_Q1_Q2.ipynb`
   - Performs data exploration
   - Conducts peak age analysis
   - Develops rating systems
   - Saves processed data

2. **Second:** Run `horse_racing_analysis_Q3.ipynb`
   - Builds predictive models
   - Evaluates model performance
   - Saves model predictions

3. **Third:** Run `horse_racing_analysis_Q4.ipynb`
   - Compares with market odds
   - Analyzes betting strategies
   - Generates final insights

### View Complete Report
Open `Horse_Racing_Report.html` in any web browser for the full analysis report with all visualizations and findings.

---

## 💡 Skills Demonstrated

### Data Science:
✅ Large-scale data processing (777K+ records)  
✅ Exploratory data analysis (EDA)  
✅ Feature engineering & selection  
✅ Statistical hypothesis testing  
✅ Time series analysis  

### Machine Learning:
✅ Classification modeling  
✅ Model comparison & evaluation  
✅ Hyperparameter tuning  
✅ Cross-validation  
✅ Feature importance analysis  

### Business Analytics:
✅ Domain knowledge application  
✅ Market analysis  
✅ ROI & financial metrics  
✅ Data-driven recommendations  
✅ Stakeholder reporting  

---

## 📊 Sample Visualizations

The project includes comprehensive visualizations:
- Performance distribution by age
- Feature correlation heatmaps
- Model comparison charts
- ROC curves and confusion matrices
- Market odds vs. model predictions
- Betting strategy performance over time

---

## 🎓 Academic Context

This project was completed as part of quantitative analysis training, demonstrating:
- Rigorous statistical methodology
- Reproducible research practices
- Clear documentation and reporting
- Professional-grade code organization

---

## 📝 Future Enhancements

Potential extensions for this project:
- [ ] Real-time prediction API
- [ ] Integration of weather and track condition data
- [ ] Deep learning models (LSTM for sequential race data)
- [ ] Interactive dashboard for live race analysis
- [ ] Automated betting strategy backtesting framework

---

## 👤 Author

**Vindya Siriwardhana**
- MSc Data Science - University of Essex
- MSc Applied Statistics - University of Colombo
- 📧 asvindyaravi@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/vindya-siriwardhana/)
- 🔗 [GitHub](https://github.com/YOUR_GITHUB_USERNAME)

---

## 📄 License

This project is available for educational and portfolio purposes.

---

## 🙏 Acknowledgments

- Dataset source: [https://drive.google.com/file/d/1DiPN6S-EycuqBQs73HNqLSkmOFaVAYaZ/view?usp=sharing]
- Analysis framework inspired by quantitative finance methodologies
- Statistical approaches validated against sports analytics literature

---

## 📞 Contact

For questions, collaboration opportunities, or discussions about this project:
- Email: asvindyaravi@gmail.com
- LinkedIn: [Vindya Siriwardhana](https://www.linkedin.com/in/vindya-siriwardhana/)

---

**⭐ If you found this project interesting, please consider starring the repository!**
