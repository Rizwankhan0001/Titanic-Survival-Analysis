# 🚢 Titanic Survival Analysis

A comprehensive data analysis project exploring passenger survival patterns from the infamous RMS Titanic disaster of 1912.

## 📊 Project Overview

This project analyzes the Titanic passenger dataset to uncover insights about survival factors and patterns. Using Python and data science libraries, we explore relationships between passenger characteristics and their likelihood of survival.

## 🎯 Objectives

- Analyze passenger demographics and survival rates
- Identify key factors that influenced survival chances
- Perform data cleaning and preprocessing
- Create visualizations to illustrate findings
- Apply statistical analysis techniques

## 📁 Dataset

The analysis uses the famous Titanic dataset containing information about 891 passengers:
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Sex**: Gender of passenger
- **Age**: Age of passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Passenger fare
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Seaborn** - Statistical data visualization
- **Matplotlib** - Plotting library
- **Jupyter Notebook** - Interactive development environment

## 📋 Analysis Steps

1. **Data Loading & Exploration**
   - Import dataset and examine structure
   - Check data types and basic statistics

2. **Data Cleaning**
   - Handle missing values in Age and Embarked columns
   - Remove unnecessary columns (Cabin, Ticket, Name, PassengerId)
   - Fill missing ages with median values

3. **Exploratory Data Analysis**
   - Survival rate analysis by different factors
   - Statistical summaries and correlations
   - Data visualization and pattern identification

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas seaborn matplotlib jupyter
```

### Running the Analysis
1. Clone this repository
2. Ensure `train.csv` is in the project directory
3. Open `Titanic_Analysis.ipynb` in Jupyter Notebook
4. Run all cells to execute the analysis

## 📈 Key Findings

*Analysis results and insights will be documented here as the project progresses*

## 📝 Files Structure

```
Titanic_Project/
├── README.md                 # Project documentation
├── Titanic_Analysis.ipynb    # Main analysis notebook
└── train.csv                # Dataset file
```

## 👨‍💻 Author

**Rizwan Khan**
- GitHub: [@Rizwankhan0001](https://github.com/Rizwankhan0001)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*"The sea, once it casts its spell, holds one in its net of wonder forever." - Jacques Cousteau*