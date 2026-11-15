# Credit Risk Management Platform
This project focuses on developing a Credit Risk Management Platform that combines a Probability of Default (PD) prediction model with an interactive Power BI dashboard to help lending institutions assess borrower credit risk, monitor loan portfolio performance and understand how changing economic conditions can affect loan defaults.

Our project uses the Lending Club peer-to-peer lending dataset, which contains approximately 393,000 loan records from 2008 to 2016, together with macroeconomic indicators obtained from the Federal Reserve Economic Data (FRED) database.

## Main Project Outputs 
1. Probability of Default (PD) Model - A TensorFlow-based Artificial Neural Network was developed to estimate the likelihood of borrowers defaulting on their loans. SHAP was also used to identify the main factors influencing default predictions, helping to make the model's results easier to understand.

2. Power BI Credit Risk and Portfolio Stress Testing Platform - ALL the model outputs were integrated into an interactive Power BI platform to support borrower-level and portfolio-level credit risk analysis. The platform allows users to analyse borrower risk, monitor portfolio performance, and evaluate the impact of changing economic conditions on credit risk exposure using 3 main dashboards:

   - The Executive Portfolio Dashboard: To provide an overview of loan performance, portfolio exposure, average Probability of Default and other key risk indicators.
   - The Borrower Risk Assessment Dashboard: To allow users to assess individual borrowers, view their predicted default probabilities, risk categories and the main factors influencing their risk scores.
   - The Portfolio Stress Testing Dashboard: To evaluate how different economic conditions, including changes in interest rates, unemployment, inflation and GDP growth, may affect portfolio risk.
