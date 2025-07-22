📊 Insurance Cost Prediction – Data Science Project

This project analyzes and predicts individual medical insurance costs using demographic and health-related data. The goal is to build a regression model that estimates insurance charges based on key features such as age, BMI, smoking status, region, and more.
📁 Project Structure

    insurance cost project.ipynb:
    Jupyter notebook containing the full workflow, from data analysis to model training and evaluation.

🗃️ Dataset Overview

The dataset includes the following columns:
Column	Description
age	Age of the primary beneficiary
sex	Gender of the beneficiary
bmi	Body Mass Index
children	Number of children covered by insurance
smoker	Smoking status (yes / no)
region	Residential area in the US
charges	Medical costs billed by health insurance
🔄 Workflow
1. 📥 Data Loading & Exploration

    Load the dataset and inspect its structure.

    Visualize feature distributions.

    Analyze correlations between features and the target (charges).

2. 🧹 Data Preprocessing

    Handle missing values (if any).

    Encode categorical variables (sex, smoker, region) using techniques like One-Hot Encoding or Label Encoding.

    Apply feature scaling if needed (e.g., StandardScaler).

3. 🤖 Model Building

    Split the data into training and testing sets.

    Train multiple regression models:

        Linear Regression

        Random Forest Regressor

        (Optional) XGBoost or other advanced models

    Evaluate model performance using:

        RMSE (Root Mean Squared Error)

        MAE (Mean Absolute Error)

        R² Score (Coefficient of Determination)

4. 📈 Results & Interpretation

    Plot predictions vs. actual values.

    Analyze feature importance.

    Discuss model performance and suggest improvements.

▶️ How to Run
Step 1: Clone this repository or download the notebook


Step 2: Install required packages

Ensure Python 3.x is installed, then run:

pip install pandas numpy matplotlib seaborn scikit-learn

Step 3: Launch Jupyter Notebook

jupyter notebook

Then open insurance cost project.ipynb and run the cells sequentially.
✅ Results

    Visualizations show clear relationships between smoker, age, bmi, and insurance costs.

    Feature importance highlights smoking status and BMI as top contributors.

    Regression model performance metrics are displayed in the final evaluation section.

📄 License

This project is for educational purposes only and free to use or modify.
