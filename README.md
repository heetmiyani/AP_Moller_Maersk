# AP_Moller_Maersk

# INTRODUCTION

The provided dataset appears to contain information related to product sourcing, with various attributes for each product. Here's a brief introduction to the dataset:

Columns:

ProductType: Categorical variable indicating the type or category of the product.
Manufacturer: Categorical variable representing the manufacturer of the product.
Area Code: Categorical variable denoting the area code associated with the product's sourcing location.
Sourcing Channel: Categorical variable specifying the channel through which the product is sourced (e.g., wholesale, retail, e-commerce).
Product Size: Categorical variable indicating the size of the product (e.g., large, small).
Product Type: Categorical variable denoting additional type information about the product.
Month of Sourcing: Date-time variable representing the month and year when the product was sourced.
Sourcing Cost: Numerical variable indicating the cost associated with sourcing the product.

Sample Entries:

The dataset contains multiple entries, each representing a unique product.
Each entry includes information such as the product's type, manufacturer, sourcing channel, size, sourcing location, and cost.
Additionally, there is a column specifying the month and year of sourcing, allowing for temporal analysis.

# Methodology

The provided code performs a comprehensive analysis of a dataset containing information about product sourcing transactions. Initially, exploratory data analysis (EDA) is conducted to understand the dataset's structure, including the distribution of categorical variables, visualization of numerical features, and identification of potential outliers. Following EDA, data preprocessing steps are implemented, including one-hot encoding of categorical variables and handling missing values.

Subsequently, predictive modeling is performed using various regression algorithms, including Linear Regression, Ridge Regression, Gradient Boosting Regression, and Random Forest Regression. Each model is trained and evaluated using appropriate evaluation metrics such as mean squared error (MSE), root mean squared error (RMSE), and R-squared (R2) score. Grid search with cross-validation is employed to optimize hyperparameters for the Random Forest Regression model, enhancing its predictive performance.

Finally, the evaluation metrics for each model are calculated and compared to assess their predictive capabilities. Additionally, visualizations such as boxplots and count plots are generated to provide insights into the relationships between different variables and the target variable (Sourcing Cost). Overall, the code implements a robust end-to-end workflow for data analysis, preprocessing, modeling, and evaluation, enabling a comprehensive understanding of the dataset and facilitating informed decision-making.


