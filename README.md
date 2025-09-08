# HR-Attrition-Prediction-Project
The goal of this project is to provide machine learning capabilities to forecast employee attrition and identify significant variables such as overtime, compensation, and promotions that lead to turnover. This analysis is presented through a Power BI dashboard to help support Human Resource decisions.

 Overview and Purpose of Project:
  -This project investigates employee attrition through the HR dataset and develops predictive models to determine the attributes that are leading to employee turnover. The intention is to illustrated how HR teams can use data and make decisions that focus on retaining top talent.


 Tools:
  -Python (pandas, scikit-learn, SHAP, matplotlib, seaborn)
  -Power BI
  -Jupyter notebook
  -Excel as CSV for exporting files.


Project Layout:
  -This is a breakdown of the most notable files included:


  1.HR_Attrition_Model.ipynb
    →This is a Python notebook that consists of:
        -Data cleaning and exploratory data analysis
        -Machine learning models (Logistic regression, Decision tree)
        -Model evaluation (Accuracy, confusion matrix)
        -SHAP value analysis (evaluation of features importance)
        -CSV data export of the predictions.


  2.HR_Attrition_Prediction_Dashboard.pbix
    → This is a power BI dashboard file that includes:
        -Interactive visuals to breakdown the attrition.
        -Actual vs predicted attrition.
        -Filters implemented to select between departments, job roles, genres, etc.


  3.HR_Attrition_Report.pdf
    → This was a business summary documentation which incorporated:
        -Project objectives.
        -Key findings.
        -Model performances.
        -SHAP Explanations.
        -HR Recommendations.


  4.Attrition_Predictions.csv
    →This is the exported predictions, included:
      -Actual attrition.
      -Predicted attrition.
      -Employee attributes related to the dataset that were also used to build the power BI dashboard. 

 Key Findings:
  -Overtime, low salary and long time since promoted produced the strongest associations to attrition.
  -Single and younger employees had a higher risk of attrition. 
  -The Decision tree model produced strong accuracy while also offering better explanatory power. 


 Contact:
  For questions or collaboration, feel free to reach out at:
  [mohammedkamilhussain2911@gmail.com] | [linkedin.com/in/mohammed-kamil-hussain-4203422b4]
