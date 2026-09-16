# Smart Mobility & Ride Analytics

## Project Overview
Smart Mobility & Ride Analytics is a data science project that explores a ride-hailing business dataset to understand trip patterns, fare pricing, customer ratings, and operational performance.

As an aspiring data scientist, I developed this project to apply Python, mathematics, probability, statistics, and hypothesis testing to real-world business questions. The objective is to discover meaningful patterns, validate assumptions using statistical evidence, and support data-driven decision-making.

## Objectives
- Prepare and clean the dataset using NumPy and Pandas.
- Analyze the relationship between trip distance and fare amount.
- Compare premium and economy ride prices.
- Investigate surge pricing and customer ratings.
- Compare revenue during peak and non-peak hours.
- Identify unusual fare values and potential anomalies.
- Estimate ride demand probabilities for different ride categories.
- Explore operational factors related to business performance.
- Use statistical evidence to evaluate possible pricing and service improvements.

## Dataset
**Dataset name:** Trip_Analysis Dataset  
**File:** `Trip_Analysis.xlsx`

The dataset contains ride-hailing trip information used for statistical analysis. The notebook examines the dataset structure, relevant variables, and data quality before performing the analysis.

Place the Excel dataset in the project folder when running the notebook locally, or upload it when prompted in Google Colab.

## Tools and Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- Jupyter Notebook / Google Colab

## Project Structure
Smart-Mobility-Ride-Analytics/
├── Module_III_Assignment_VI.ipynb
├── Trip_Analysis.xlsx
└── README.md
```

## Analysis Performed
### 1. Trip Distance and Fare Amount
Pearson correlation, covariance, and linear algebra concepts are used to investigate the relationship between trip distance and fare amount.

### 2. Premium vs. Economy Ride Pricing
Descriptive statistics and statistical tests, including t-tests or ANOVA, are used to compare ride prices across categories.

### 3. Surge Pricing and Customer Ratings
Spearman correlation and significance testing are used to examine the relationship between surge pricing and customer ratings.

### 4. Peak-Hour vs. Non-Peak Revenue
A statistical comparison using a t-test or z-test is used to investigate revenue differences between peak-hour and non-peak rides.

### 5. Fare Anomaly Detection
Quartiles, percentiles, the Interquartile Range (IQR), and z-scores are used to identify unusual fare values that may require further investigation.

### 6. Ride Demand Probability
Basic probability, conditional probability, and Bayes’ theorem are applied to estimate demand probabilities for different ride categories.

### 7. Operational Factors and Business Performance
Pearson and Spearman correlation, covariance, and eigenvalue analysis are used to explore relationships among operational variables.

### 8. Statistical Evidence for Improvements
Confidence intervals, bootstrapping, and hypothesis testing are used to assess evidence that may support pricing or service improvements.

## Installation
Install the required Python libraries:
```bash
pip install numpy pandas matplotlib scipy openpyxl jupyter
```

## How to Run the Project
### Option 1: Google Colab
1. Open `Module_III_Assignment_VI.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. When prompted, upload `Trip_Analysis.xlsx`.
4. Review the outputs, visualizations, and statistical interpretations.

### Option 2: Run Locally
1. Download or clone this repository.
2. Install the required libraries.
3. Place `Trip_Analysis.xlsx` in the project directory.
4. Open the notebook in Jupyter Notebook or VS Code.
5. Update the Excel file path if necessary.
6. Run the notebook cells in order.

## Results and Business Insights
The notebook is designed to produce statistical outputs and interpretations for all eight analysis questions. The findings can help identify pricing patterns, ride demand characteristics, unusual fares, and operational relationships.

**Note:** Conclusions and recommendations should be based on the actual dataset results, statistical significance, and the limitations of the analysis. An observed relationship does not necessarily establish causation.

## Learning Outcomes
- Data preparation and exploratory data analysis.
- Applying mathematical and statistical concepts using Python.
- Conducting correlation analysis and hypothesis testing.
- Estimating probabilities and confidence intervals.
- Interpreting analytical results for business decision-making.
- Communicating data-driven insights.

## Conclusion
Smart Mobility & Ride Analytics demonstrates my ability to apply data science concepts to a real-world business problem. This project represents my learning journey toward becoming a data scientist and strengthening my skills in Python, statistical analysis, and evidence-based decision-making.

