# Customer Churn Prediction

## Overview
This project aims to predict customer churn using machine learning techniques. The dataset used contains customer information, including demographics and account details, which are analyzed to identify patterns and factors contributing to customer churn.

## Technologies Used
- **Python**: The primary programming language for data analysis and modeling.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Seaborn & Matplotlib**: For data visualization.
- **Plotly**: For interactive visualizations.
- **Scikit-learn**: For machine learning algorithms and model evaluation.
- **XGBoost**: For gradient boosting classification.
- **Random Forest**: For ensemble learning.

## Dataset
The dataset used in this project is `Churn_Data.csv`, which contains various features related to customer demographics and their churn status.

## Steps Involved
1. **Data Importing**: Load the necessary libraries and the dataset.
2. **Data Preprocessing**:
   - Check for missing values and data types.
   - Drop irrelevant features (e.g., `Surname`, `Gender`, `RowNumber`, `CustomerId`).
   - Encode categorical variables using `LabelEncoder`.
3. **Data Visualization**:
   - Visualize customer distribution by geography using pie charts.
   - Analyze churners and non-churners based on age and salary distributions.
4. **Model Training**:
   - Split the dataset into training and testing sets.
   - Train models using XGBoost and Random Forest classifiers.
5. **Model Evaluation**:
   - Evaluate model performance using accuracy scores and classification reports.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook predict_customerchurn.ipynb
   ```
4. Run the cells in the notebook to execute the analysis and model training.

## Results
The project provides insights into customer churn patterns and the performance of different machine learning models. The accuracy scores of the models are printed at the end of the notebook.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.