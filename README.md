# Telecommunications Customer Churn Dashboard

This project involves the development of a data visualization dashboard aimed at understanding customer churn in the telecommunications industry. The dashboard utilizes data from IBM’s sample dataset to explore customer behavior and predict which customers are likely to discontinue services.

## Project Overview

The primary objective of this project is to analyze customer churn and identify the key factors that influence it. By visualizing patterns and trends using various charts and graphs, the dashboard helps stakeholders make data-driven decisions to improve customer retention.

### Key Features
- **Data Cleaning**: Ensures that the dataset is prepared for analysis by removing duplicates, handling missing values, and formatting inconsistencies.
- **Exploratory Data Analysis (EDA)**: Provides insights into customer demographics and their subscription patterns.
- **Customer Churn Analysis**: Investigates the relationship between customer attributes (tenure, monthly charges, total charges, service type, etc.) and churn rates.
- **Interactive Visualizations**: Users can interact with the dashboard, drill down into specific segments, and explore detailed customer behaviors.

## Technologies Used

- **Tableau**: For creating and deploying the interactive dashboard.
- **Python**: Used for data cleaning and preparation.
- **Pandas**: For data manipulation and handling.
- **Matplotlib**: For initial exploratory visualizations.

## Dataset

The dataset used in this project is sourced from IBM’s Sample Data Sets and includes various customer attributes like:
- Demographics (e.g., gender, senior citizen status)
- Service subscriptions (e.g., phone service, internet service)
- Account information (e.g., tenure, monthly charges, total charges)
- Churn status

You can find the dataset [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Dashboard Visualizations

1. **Customer Churn Distribution**: A pie chart showing the percentage of customers who have churned.
2. **Tenure Distribution**: A histogram to visualize how long customers stay with the service before churning.
3. **Charges Distribution**: Histograms for monthly and total charges, showing how pricing impacts churn.
4. **Churn by Demographics**: Bar charts for senior citizens, partners, dependents, and phone service, segmented by churn status.
5. **Lifestyle Segmentation**: Analysis of customer lifestyle segments (e.g., independent, earners) and their churn rates.
6. **Scatter Plots**: Plots showing relationships between tenure, monthly charges, and total charges with churn as a color overlay.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/customer-churn-dashboard.git
   
2. Install required Python libraries:
pip install -r requirements.txt

3. Open the Tableau file to explore the dashboard, or run the Python scripts to preprocess the dataset:
python preprocess_data.py --input data/telco_churn.csv

Future Enhancements
Advanced Predictive Modeling: Implement machine learning algorithms to predict churn more accurately.
Real-time Analysis: Integrate real-time data sources to update the dashboard dynamically.

Contributors
Ashkan Sheikhansari
