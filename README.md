# **Crime Data Analysis and Predictive Modeling**

## **Introduction**
This project focuses on analyzing crime data and building predictive models to classify the severity of crimes. The dataset includes various features such as the victim's age, gender, area of occurrence, and crime status.

## **Data Collection**
The dataset used in this project contains records of crimes reported in various areas. It includes fields like:
- **Date Rptd**
- **DATE OCC**
- **Vict Age**
- **Vict Sex**
- **AREA NAME**
- **Part 1-2**
- **Status**

## **Data Preprocessing**
Preprocessing steps include:
- **Date Conversion**: Converting date columns to `datetime` format.
- **Feature Encoding**: Encoding categorical variables into numerical formats using Label Encoding and One-Hot Encoding.
- **Feature Selection**: Selecting relevant features for analysis and modeling.

## **Data Visualization**
Key visualizations include:
- **Crime Counts by Area**: Bar chart showing the number of crimes in each area.
- **Distribution of Victim Ages**: Histogram of victim age distribution.
- **Victim Gender Distribution**: Bar chart showing crime distribution by gender.
- **Crime Severity**: Pie chart of crime severity (Part 1 vs. Part 2).
- **Correlation between Victim Age and Gender**: Scatter plot exploring the relationship between victim age and gender.

## **Predictive Modeling**
Several machine learning models were built, including:
- **Logistic Regression**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Naive Bayes**

## **Model Evaluation**
Each model was evaluated based on:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**

## **Conclusion**
The project successfully analyzed crime data and built predictive models with varying degrees of accuracy. The Random Forest classifier was the best-performing model.

## **Future Work**
Future enhancements could include:
- **Feature Engineering**: Creating new features based on existing data.
- **Hyperparameter Tuning**: Optimizing model parameters for better performance.
- **Integration with Real-Time Data**: Incorporating real-time crime data for up-to-date predictions.

## **Installation**
To run this project locally, follow these steps:
1. **Clone the Repository**: `git clone https://github.com/your-repo/crime-data-analysis.git`
2. **Install Dependencies**: `pip install -r requirements.txt`
3. **Run the Notebook**: Launch Jupyter Notebook and open `Crime_Analysis.ipynb`

## **Usage**
This project can be used for:
- **Crime Data Analysis**: Understanding crime trends and patterns in different areas.
- **Predictive Modeling**: Building models to predict the severity of future crimes.
- **Visualization**: Generating insightful visualizations for presentations or reports.

## **Contributing**
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or new features.

