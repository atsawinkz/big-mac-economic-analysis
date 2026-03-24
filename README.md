# Big Mac Index: Linear Regression Analysis

## Project Overview and Learning Objectives
This project explores the application of **Simple Linear Regression** and **Multiple Linear Regression** algorithms using the Big Mac Adjusted Index dataset. The primary learning objectives are to:
- Understand the fundamentals of linear regression algorithms.
- Learn how to prepare and analyze real-world datasets for machine learning.
- Build predictive models to estimate target variables based on various features.
- Evaluate model performance using standard metrics.

## Dataset Sources and Descriptions
- **Source**: Big Mac Adjusted Index
- **File**: `data/big-mac-adjusted-index.csv`
- **Description**: This dataset contains economic indicators related to the Big Mac index across various countries and time periods. It is used to compare purchasing-power parity (PPP) and currency valuation.

## Installation Requirements
To run the Jupyter Notebooks locally, you need to install the required Python libraries.

1. Clone the repository:
   ```bash
   git clone <your-repository-url>
   cd <repository-name>
   ```

2. (Optional but recommended) Create a virtual environment:
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Step-by-Step Tutorials
1. Navigate to the `notebooks/` directory.
2. Open `Simple_Linear_Regression.ipynb` to understand how a single feature can be used to predict a continuous target variable.
3. Open `Multiple_Linear_Regression.ipynb` to see how multiple features can improve the model's predictive capability.
4. Run the cells sequentially to observe data preprocessing, model training, and evaluation steps.

## Key Findings and Insights
- **Simple Linear Regression**: Explains the foundational relationship between the dependent and a single independent variable.
- **Multiple Linear Regression**: Highlights how combining multiple economic indicators (features) impacts the overall model accuracy, capturing more variance in the Big Mac Index.
- Data visualization techniques (using `matplotlib` and `seaborn`) play a crucial role in identifying patterns and correlations prior to model building.

## Usage Examples
To experiment with the models:
1. Start the Jupyter environment:
   ```bash
   jupyter notebook
   ```
2. Open the relevant notebook from the `notebooks/` folder.
3. Review or modify the data loading cells (e.g., `pd.read_csv('../data/big-mac-adjusted-index.csv')`).
4. Experiment with different parameters, features, or regression techniques to see how the model's accuracy changes.
