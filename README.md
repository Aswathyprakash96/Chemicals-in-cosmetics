# CHEMICALS IN COSMETICS
The aim of the project is identify the amount of chemical substances present in a Cosmetic  product.The California Safe Cosmetics Program (CSCP), administered by the California Department of Public Health (CDPH), is a vital initiative designed to protect public health by monitoring and disclosing hazardous ingredients in cosmetic products sold in California.
 The program, established under the California Safe Cosmetics Act, requires cosmetic manufacturers, packers, and distributors to report products containing ingredients that are known or suspected to cause cancer, birth defects, or other developmental or reproductive harm.
# Goal of the Project
* Identify trends in the use of chemicals known or suspected to cause cancer, birth defects, or other developmental or reproductive harm within the cosmetic industry.
* Evaluate the compliance of manufacturers with the reporting requirements set by the California Safe Cosmetics Act, and assess the completeness of the data collected by the CSCP.
* Increase awareness about the potential health risks associated with certain cosmetic ingredients, and provide insights into how these chemicals are distributed across different product categories and brands.
* Highlight gaps in the reporting process, including missing data or products that may not be included, and suggest ways to improve transparency and safety within the cosmetics industry.
* Support consumer education by presenting the data in a user-friendly format, helping consumers make more informed decisions about the personal care products they use.
  # Dataset
  * Ingredients List: A list of chemicals or substances present in each product.
  * Concentration of Chemicals: The amount of each chemical present.
  * Product Type: Type/category of cosmetic product (e.g., lotion, shampoo, face cream).
  * Safety Information: Whether the product contains substances known to cause cancer, birth defects, or reproductive harm.
 # Machine Learning Models Used
 * Linear Regression: A basic linear approach to model relationships between variables.
 * Decision Tree Regressor: A non-linear model capable of capturing complex relationships.
 * Random Forest Regressor: An ensemble method using multiple decision trees for improved accuracy.
 * Gradient Boosting Regressor: Another ensemble method using boosting to reduce error.
 * Support Vector Regressor (SVR): A powerful regression technique based on Support Vector Machines.
# Performance Evaluation
* Mean Absolute Error (MAE): Measures the average magnitude of errors in predictions.
* Mean Squared Error (MSE): Measures the average of the squares of errors, emphasizing larger errors.
* Root Mean Squared Error (RMSE): The square root of MSE, providing error in the original unit of measurement.
* R² Score: Represents how well the model explains the variance of the target variable
# Conclusiom
*  Among the models evaluated, the Random Forest Regressor model, which appears to be the best performing, demonstrated the highest R² score of 0.8319, indicating a strong fit to the data.
*  This suggests that it effectively captures the underlying patterns of the dataset and provides the most accurate predictions.
*   The Support Vector Regressor (SVR) also exhibited strong performance with an R² score of 0.7253 and an RMSE of 0.3417, showing that it can reliably predict outcomes while maintaining a relatively low error.
* Additionally, the Decision Tree Regressor (R² = 0.7215) performed well, indicating its capability to model complex, non-linear relationships in the data.
* However, the Linear Regression model performed poorly with an R² score of 0.0957, which indicates that it failed to capture the relationships between the features and the target variable, and therefore does not offer useful predictions for this
* The Random Forest Regressor and Gradient Boosting Regressor both provided moderate results, with R² scores of 0.5105, indicating that while they can capture some patterns, they may not be as effective as the top performers.
    
